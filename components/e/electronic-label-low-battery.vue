<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hal5zdbds"/><path class="ndtxmi_-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electronic-label-low-battery" /></template>
<style>
.hal5zdbds {
  d: path("M11.2 18H2.5V5h19v7.7");
}

.ndtxmi_-n {
  d: path("M8.75 9.75C8.5 9 8 8.5 7 8.5S5.25 9 5.25 10c0 1.5 3.5 1 3.5 3c0 1-.75 1.5-1.75 1.5s-1.5-.5-1.75-1M7 7.25V8.5m0 6v1.25M11.5 9H18m-4 6.5h6.5v5H14Zm7.75 1.5v2m-6-1h.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
