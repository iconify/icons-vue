<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cy_dxjx6y"/><path class="ycpmlctqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-style-smock" /></template>
<style>
.cy_dxjx6y {
  d: path("m9.5 3l-4 1Q4.25 4.5 4 6L2.5 17h3l1-7v11.5h11V10l1 7h3L20 6q-.25-1.5-1.5-2l-4-1L12 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ycpmlctqm {
  d: path("M12.25 12h2.5v2.5h-2.5Z");
}

</style>
