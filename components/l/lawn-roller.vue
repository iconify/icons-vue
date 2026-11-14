<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eq9l0hy6h"/><path class="t4-_2pb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lawn-roller" /></template>
<style>
.eq9l0hy6h {
  d: path("M15 11.5H6.5a2.5 4.5 0 0 0 0 9H15");
}

.t4-_2pb1y {
  d: path("M12.5 16a2.5 4.5 0 1 0 5 0a2.5 4.5 0 1 0-5 0Zm2.5-4.5l2.5-8m-1.5 0h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
