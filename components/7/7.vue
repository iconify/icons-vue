<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="svgIDa" x1="64" x2="64" y1="102.5" y2="24.97" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vlzxxcccm"/><stop offset=".515" class="j1rdzyw_l"/></linearGradient><path fill="url(#svgIDa)" class="byd9h-lnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:7" /></template>
<style>
.byd9h-lnj {
  d: path("M90.16 33.44L60.5 100.77c-.33.75-1.07 1.23-1.88 1.23h-8.76c-1.5 0-2.49-1.55-1.87-2.92l27.64-59.99c.63-1.36-.37-2.92-1.87-2.92H39.72c-1.14 0-2.06-.92-2.06-2.06v-6.07c0-1.14.92-2.06 2.06-2.06h48.56c1.14 0 2.06.92 2.06 2.06v4.56c-.01.3-.07.58-.18.84z");
}

.j1rdzyw_l {
  stop-color: var(--svg-color--504f4f, #504F4F);
}

.vlzxxcccm {
  stop-color: var(--svg-color--757575, #757575);
}

</style>
