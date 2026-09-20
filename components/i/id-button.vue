<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dpvarpbiq"/><path class="q-_fbfbpi"/><path class="sc5o1nzqk"/><path class="ejmwlibpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:id-button" /></template>
<style>
.dpvarpbiq {
  fill: var(--svg-color--8e24aa, #8e24aa);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.ejmwlibpg {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M29.19 36.87h10.35v54.89H29.19zm22.85 0h18.55c5.72 0 10.71 1.15 14.95 3.45q6.36 3.45 9.81 9.66t3.45 14.34t-3.45 14.34t-9.81 9.66c-4.24 2.3-9.23 3.45-14.95 3.45H52.04zm18.09 45.08c5.93 0 10.45-1.57 13.57-4.71s4.68-7.45 4.68-12.92s-1.56-9.78-4.68-12.92s-7.64-4.71-13.57-4.71h-7.74v35.27h7.74z");
}

.q-_fbfbpi {
  fill: var(--svg-color--ab47bc, #ab47bc);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

.sc5o1nzqk {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
