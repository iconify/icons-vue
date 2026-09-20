<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedBoring0)" class="cn3atzb_i"/><defs><linearGradient id="tokenBrandedBoring0" x1="12" x2="12" y1="2" y2="22" gradientUnits="userSpaceOnUse"><stop class="z1wq4yhbp"/><stop offset="1" class="vqxsj7big"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:boring" /></template>
<style>
.cn3atzb_i {
  d: path("M12.002 22A10 10 0 1 0 8.877 2.5V12a3.125 3.125 0 1 0 3.125-3.125h-1.875v-1.25h1.875A4.375 4.375 0 1 1 7.627 12V3c-.438.219-.85.462-1.25.731v8.27a5.625 5.625 0 1 0 5.625-5.626h-1.875v-1.25h1.875A6.875 6.875 0 1 1 5.127 12V4.738A10 10 0 0 0 12.002 22m1.875-10a1.875 1.875 0 1 1-3.75 0v-1.875h1.875A1.875 1.875 0 0 1 13.877 12");
}

.ft5dv1b6b {
  fill: none;
}

.vqxsj7big {
  stop-color: var(--svg-color--015dd2, #015DD2);
}

.z1wq4yhbp {
  stop-color: var(--svg-color--0071e1, #0071E1);
}

</style>
