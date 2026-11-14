<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b77crrbsu"/><path class="y1u9pf9uw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:geneticist" /></template>
<style>
.b77crrbsu {
  d: path("M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3.5 21c0-4 3.25-6.5 7.5-6.5q.873 0 1.682.138M15.5 15c0 3.25 5 3.25 5 6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y1u9pf9uw {
  d: path("M20.5 15c0 3.25-5 3.25-5 6.5m.25-5.5h4.5m-4.5 4.5h4.5");
}

</style>
