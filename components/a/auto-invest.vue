<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y3q4v0k2f"/><path class="xtwinbqpl"/><path class="is8nqnbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:auto-invest" /></template>
<style>
.is8nqnbzt {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xtwinbqpl {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m1.75 14A2.75 2.75 0 1 1 18 15.75");
}

.y3q4v0k2f {
  d: path("M3.5 3v17.5h9.3");
}

</style>
