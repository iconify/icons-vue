<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fk5n61baj"/><path class="qobmkes1t"/><path class="ye1w1bb5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cave-crawl" /></template>
<style>
.fk5n61baj {
  d: path("M2.5 20L5 10l4.5-5l5.5.5l4 4.5l2.5 10Z");
}

.qobmkes1t {
  d: path("M6.5 20v-4a5.5 5.5 0 0 1 11 0v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ye1w1bb5x {
  d: path("M9.25 15.5h5.5m-2-2l2 2l-2 2");
}

</style>
