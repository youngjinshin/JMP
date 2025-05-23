## JMP 체험판 다운로드

[https://www.jmp.com/ko/offers/jmp-free-trial](https://www.jmp.com/ko/offers/jmp-free-trial)

---

## JMP 설치 후 언어 변경(한글 → 영어)

### (권장) 자동 변경 스크립트

- Windows

    ```sh
    en_win.bat
    ```
- Mac

    ```sh
    sudo ./en_mac.sh
    ```

### 수동 변경 방법

<details closed>
<summary>Windows (클릭)</summary>

1. 실행(Win + R) - `regedit`

    ![image](https://github.com/user-attachments/assets/27c54664-c635-4b4f-9e48-b025726168f2)

2. 주소창에 `HKCU\Software\JMP\JMP\18.0\Options` 입력
3. `LanguagePref` 값 데이터를 `en`으로 변경

    ![image](https://github.com/user-attachments/assets/e435f5e5-4af5-4bf2-9eda-acf343b02235)

</details>

<details closed>
<summary>Mac (클릭)</summary>

1. `/Applications/JMP 18.app/Contents/Resources` 디렉토리로 이동
2. `ko.lproj` 백업 후 삭제
3. `en.lproj` → `ko.lproj` 복사 후 이름 변경

</details>
