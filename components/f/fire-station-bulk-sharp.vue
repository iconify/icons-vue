<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bpp7y5g_r"/><path class="gfe54vb_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fire-station-bulk-sharp" /></template>
<style>
.bpp7y5g_r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gfe54vb_g {
  d: path("M10.214 9.164c-.338-.666-.434-1.393-.209-2.112c.233-.746.77-1.352 1.37-1.833a1.002 1.002 0 0 1 1.606.585c.175.873.718 1.57 1.419 2.096a1 1 0 0 1 .107.093c.922.923 1.193 2.143 1.193 3.407a3.7 3.7 0 0 1-.291 1.44a3.7 3.7 0 0 1-.793 1.176A3.7 3.7 0 0 1 12 15.1a3.7 3.7 0 0 1-2.616-1.084A3.7 3.7 0 0 1 8.3 11.4c0-.406.061-.814.204-1.195c.12-.32.296-.62.539-.862a1 1 0 0 1 1.171-.179m2.921.287a6.2 6.2 0 0 1-1.026-.986l.003.006c.112.202.22.409.294.629c.176.523.213 1.173-.006 1.69a1.905 1.905 0 0 1-2.016 1.142A1.7 1.7 0 0 0 13.7 11.4c0-.68-.081-1.43-.565-1.949M5 21v-4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0v-3H7v3a1 1 0 0 1-2 0m8 0v-4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0v-3h-2v3a1 1 0 0 1-2 0");
}

</style>
