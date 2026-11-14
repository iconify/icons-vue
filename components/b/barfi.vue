<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uqje4kcjs"/><path class="v2_dcfb1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barfi" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uqje4kcjs {
  d: path("m2.5 12l6-6l6 6l-6 6Z");
}

.v2_dcfb1x {
  d: path("M12 9.5L15.5 6l6 6l-6 6l-3.5-3.5");
}

</style>
