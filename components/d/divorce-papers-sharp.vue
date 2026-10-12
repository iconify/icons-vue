<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vc5ag39_z"/><path class="rjkooje8q"/><path class="e9cd7bjla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:divorce-papers-sharp" /></template>
<style>
.e9cd7bjla {
  d: path("m12 10.25l-1 2.25l2 1l-1 2.75");
}

.rjkooje8q {
  d: path("M12 16.25C9.5 14.75 8 13 8 11a2 2 0 0 1 4-.75a2 2 0 0 1 4 .75c0 2-1.5 3.75-4 5.25Z");
}

.vc5ag39_z {
  d: path("M4.75 2.75h14.5v18.5H4.75zM8.25 6h7.5m-7.5 12.75h7.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
