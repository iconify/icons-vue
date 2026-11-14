<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y8j47yb5y"/><path class="kiux9accd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:acceptance-criteria" /></template>
<style>
.kiux9accd {
  d: path("M6.5 12.5L8 14l2.5-2.5m2.5 1.25h4.5M6.5 17L8 18.5l2.5-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y8j47yb5y {
  d: path("M3.5 3h17v18h-17Zm0 5h17");
}

</style>
