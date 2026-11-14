<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x95ofkbri"/><path class="zg-mzsblk"/><path class="qgm7y11xy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:knee-brace" /></template>
<style>
.qgm7y11xy {
  d: path("M9 10h5m-5 4h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x95ofkbri {
  d: path("M6 7h11v10H6Zm2-4.5V7m7-4.5V7M8 17v4.5m7-4.5v4.5m2.75-17h2.5v15h-2.5Z");
}

.zg-mzsblk {
  fill: currentColor;
  d: path("M18.25 12a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

</style>
