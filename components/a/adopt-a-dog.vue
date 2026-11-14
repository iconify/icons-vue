<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kiwz0dt4l"/><path class="mdm1hwbhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adopt-a-dog" /></template>
<style>
.kiwz0dt4l {
  d: path("M11.963 18.474a4 4 0 0 1-.463.026c-2.5 0-4.5-2.25-4.5-5v-6C7 5 8.75 4 11.5 4S16 5 16 7.5v5.237");
}

.mdm1hwbhx {
  d: path("M7.5 5.25C5 4.75 3 6.5 3 10c0 2 .75 3.5 2 3.5c1 0 2-1.5 2-3m8.5-5.25C18 4.75 20 6.5 20 10c0 1.078-.218 2.011-.614 2.642m-2.69.022A3.8 3.8 0 0 1 16 10.5m-6.25-1h.01m3.49 0h.01M11.5 14h.01M18 21.5l-3-3a2 2 0 0 1 3-2.5a2 2 0 0 1 3 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
