<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="l5az3ob_r"/><path class="cazxgnbny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:boot-duotone" /></template>
<style>
.cazxgnbny {
  d: path("M192 112h-32V56a16 16 0 0 0-16-16H32a8 8 0 0 0-7.47 10.86c11.06 28.84 8.76 83.71-.22 114.93A8.3 8.3 0 0 0 24 168v32a16 16 0 0 0 16 16h26.11a16 16 0 0 0 7.16-1.69L85.89 208h16.22l12.62 6.31a16 16 0 0 0 7.16 1.69h28.22a16 16 0 0 0 7.16-1.69l12.62-6.31h16.22l12.62 6.31a16 16 0 0 0 7.16 1.69H232a16 16 0 0 0 16-16v-32a56.06 56.06 0 0 0-56-56m-48-56v24h-32a8 8 0 0 0 0 16h32v16h-32a8 8 0 0 0 0 16h80a40.07 40.07 0 0 1 39.2 32H42.25c6.74-30.84 8.16-74.17.61-104Zm61.89 144l-12.62-6.31a16 16 0 0 0-7.16-1.69h-16.22a16 16 0 0 0-7.16 1.69L150.11 200h-28.22l-12.62-6.31a16 16 0 0 0-7.16-1.69H85.89a16 16 0 0 0-7.16 1.69L66.11 200H40v-24h192v24Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.l5az3ob_r {
  d: path("M32 168c9.22-32.06 12-88.65 0-120h112a8 8 0 0 1 8 8v64h40a48 48 0 0 1 48 48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
