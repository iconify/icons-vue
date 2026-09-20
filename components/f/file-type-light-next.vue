<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGTjWo9baw" x1="336.1" x2="414.1" y1="522.5" y2="652.6" gradientTransform="translate(-8.06 -1.06)scale(.055)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="SVGb2iJM1Jt" x1="511.1" x2="511.1" y1="209.5" y2="359.9" gradientTransform="translate(-8.06 -1.06)scale(.055)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs><circle class="lmh4whbrs"/><path fill="url(#SVGTjWo9baw)" class="jwnqwybvy"/><path fill="url(#SVGb2iJM1Jt)" class="hmgte_bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-next" /></template>
<style>
.hmgte_bbe {
  d: path("M19.89 10.4h1.86v11.2H19.9z");
}

.jwnqwybvy {
  d: path("m25.26 26.5l-12.5-16.1H10.4v11.2h1.89v-8.8l11.49 14.84c.52-.35 1-.72 1.48-1.13z");
}

.lmh4whbrs {
  cx: 16px;
  cy: 16px;
  r: 14px;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
