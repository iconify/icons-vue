<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sixvpwi0r"/><path class="gnhxk5bjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kimono-sharp" /></template>
<style>
.gnhxk5bjp {
  d: path("M7 12h10v3H7z");
}

.sixvpwi0r {
  d: path("m3.62 5.5l3.51-2L8 3h8l.87.5l3.51 2l.87.5v6H17v9.25H7V12H2.75V6zm5.63-2.25l4.5 8.75m1-8.75l-2.3 4.25M7 7v4.5M17 7v4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
