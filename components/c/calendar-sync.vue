<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sa23nmb2h"/><path class="vcixxsyhk"/><path class="oqaetq4do"/><path class="ntvv1oabo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-sync" /></template>
<style>
.ntvv1oabo {
  d: path("m8.25 16.5l1.25-1.25l1.25 1.25");
}

.oqaetq4do {
  d: path("m13.25 14l1.25 1.25L15.75 14m-1.585 2.5A2.5 2.5 0 0 1 9.5 15.25");
}

.sa23nmb2h {
  d: path("M3.5 5h17v15.5h-17ZM8 3v4m8-4v4M3.5 10h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcixxsyhk {
  d: path("M9.835 14a2.5 2.5 0 0 1 4.665 1.25");
}

</style>
