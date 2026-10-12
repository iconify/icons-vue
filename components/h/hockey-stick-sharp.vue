<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g0j6imbyb"/><path class="n1p60uzkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hockey-stick-sharp" /></template>
<style>
.g0j6imbyb {
  d: path("m5.25 3l9 13.5l.589.894l1.071.006h4.34");
}

.n1p60uzkw {
  d: path("m18.75 3l-9 13.5l-.589.894l-1.071.006H3.75m5.5 2.45a2.75 1.35 0 1 0 5.5 0a2.75 1.35 0 1 0-5.5 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
