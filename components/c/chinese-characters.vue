<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dg5b0qqyz"/><path class="umey0ho2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chinese-characters" /></template>
<style>
.dg5b0qqyz {
  d: path("M3.5 3.5h17v17h-17Zm4 4.5h9M12 5v13.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.umey0ho2h {
  d: path("M12 12c-1.5 3-3 4.5-5 5.5m5-5.5c1.5 3 3 4.5 5 5.5");
}

</style>
