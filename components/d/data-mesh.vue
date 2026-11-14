<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j46bq194r"/><path class="bmqpxj0bv"/><path class="s7_6l-jkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-mesh" /></template>
<style>
.bmqpxj0bv {
  d: path("M7.75 11.5h8.5l-4.25 8l-4.25-8");
}

.j46bq194r {
  d: path("m12 3.5l-8.5 16h17L12 3.5");
}

.s7_6l-jkf {
  fill: currentColor;
  d: path("M10.5 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-4.25 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM2 19.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
