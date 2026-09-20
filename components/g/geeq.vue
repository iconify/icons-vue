<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="bkqfui07i"><path class="kocvtolop"/><path class="ca53skbog"/><path class="qmotyqz1m"/><path class="xc8g6bbqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:geeq" /></template>
<style>
.bkqfui07i {
  fill: var(--svg-color--254280, #254280);
}

.ca53skbog {
  d: path("M12 21a9 9 0 0 0 7.672-13.708l-.846.779a7.875 7.875 0 1 1-.638-.942l.83-.764A8.98 8.98 0 0 0 12 3a9 9 0 0 0-9 9a9 9 0 0 0 9 9");
}

.kocvtolop {
  d: path("M12.562 3.563h-1.124V7.5h1.124zm0 12.937h-1.124v3.937h1.124z");
}

.qmotyqz1m {
  d: path("m18.402 8.462l-.857.788a6.188 6.188 0 1 1-.603-.974l.831-.765A7.3 7.3 0 0 0 12 4.688a7.312 7.312 0 1 0 0 14.625a7.312 7.312 0 0 0 6.402-10.851");
}

.xc8g6bbqa {
  d: path("M12 6.938a5.06 5.06 0 0 1 4.11 2.105l-.837.769a3.937 3.937 0 1 0 .501 3.313h-3.212V12h3.375q-.002-.586-.162-1.12l.9-.827A5.063 5.063 0 1 1 12 6.937");
}

</style>
