<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mqkg9kykg"/><path class="tgulksb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:account-statement-sharp" /></template>
<style>
.mqkg9kykg {
  d: path("M4.25 2.75h15.5v18.5H4.25z");
}

.tgulksb_j {
  d: path("m8 8.25l4-2.5l4 2.5Zm-.25 3.25h8.5m-8.5 3h8.5m-8.5 3h5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
