<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mrr7nubfi"/><path class="njpxl_b4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:doorbuster" /></template>
<style>
.mrr7nubfi {
  d: path("M4 21.5v-19h14v10.2");
}

.njpxl_b4p {
  d: path("M4 2.5L11 5v14l-7 2.5ZM9.25 12h.01m5.49 9.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
