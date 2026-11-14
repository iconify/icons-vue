<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xrv47me9p"/><path class="j_y2mjbfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:autoclave" /></template>
<style>
.j_y2mjbfm {
  d: path("M6.25 14.75a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM17.5 11.5h.01M17.5 15v3M8 6C7 4.75 9 3.75 8 2.5M12 6c-1-1.25 1-2.25 0-3.5M16 6c-1-1.25 1-2.25 0-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xrv47me9p {
  d: path("M3 8h18v13.5H3Z");
}

</style>
