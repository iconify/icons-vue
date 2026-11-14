<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q8ul1tbcd"/><path class="kuzj75a9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:booster-pump" /></template>
<style>
.kuzj75a9y {
  d: path("M8 14.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm9.5-7.5V2.5m-2.25 2.25L17.5 2.5l2.25 2.25");
}

.q8ul1tbcd {
  d: path("M4.75 14.25a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0ZM9.5 9.5h10m-16 12.25h12M9.5 19v2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
