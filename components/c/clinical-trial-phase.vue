<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eijuybbnf"/><path class="b4yvvb2hq"/><path class="a5uqb5btg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clinical-trial-phase" /></template>
<style>
.a5uqb5btg {
  d: path("M9 14v4");
}

.b4yvvb2hq {
  fill: currentColor;
  d: path("M15 6h6v12h-6Z");
}

.eijuybbnf {
  d: path("M3 18v-4h6v-4h6v8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
