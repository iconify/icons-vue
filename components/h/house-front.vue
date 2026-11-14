<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z6zf6db1g"/><path class="c5m4p6far"/><path class="tfjt_1bjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-front" /></template>
<style>
.c5m4p6far {
  d: path("M5 9.5v11h14v-11");
}

.tfjt_1bjm {
  d: path("M10 20.5V15h4v5.5m-3.5-10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6zf6db1g {
  d: path("m2.5 11.5l9.5-8l9.5 8");
}

</style>
