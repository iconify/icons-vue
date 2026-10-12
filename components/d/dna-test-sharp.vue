<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lnnprcbev"/><path class="b-h2u6bwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dna-test-sharp" /></template>
<style>
.b-h2u6bwx {
  d: path("M10 7.5c0 2.75 4 2.75 4 5.5s-4 2.75-4 5.5m4-11c0 2.75-4 2.75-4 5.5s4 2.75 4 5.5");
}

.lnnprcbev {
  d: path("M6.75 4.75h10.5m-9.75 0h9v12a4.5 4.5 0 0 1-9 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
