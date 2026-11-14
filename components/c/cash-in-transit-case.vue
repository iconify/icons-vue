<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v6qsb93ps"/><path class="b0jpq6bpo"/><path class="pomyxrd4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cash-in-transit-case" /></template>
<style>
.b0jpq6bpo {
  d: path("M13.5 15.25H22v6.5h-8.5Z");
}

.pomyxrd4t {
  d: path("M16.5 18.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm-1 0h.01m4.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v6qsb93ps {
  d: path("M10.7 21.5H2.5V7h19v5.4M8.5 7V5A1.5 1.5 0 0 1 10 3.5h4A1.5 1.5 0 0 1 15.5 5v2M7 7v14.5M11.5 7v5.4");
}

</style>
