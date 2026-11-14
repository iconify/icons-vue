<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="on5l0gbkg"/><path class="k9mur0brr"/><path class="a7bo6jbho"/><path class="g24j7rppo"/><path class="zfk1a0bxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-expiry-input" /></template>
<style>
.a7bo6jbho {
  d: path("m9 15l2.5-6");
}

.g24j7rppo {
  fill: currentColor;
  d: path("M12.75 12.75h3.5V14h-3.5Z");
}

.k9mur0brr {
  fill: currentColor;
  d: path("M4.5 12.75H8V14H4.5Z");
}

.on5l0gbkg {
  d: path("M2 6h20v12H2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zfk1a0bxg {
  d: path("M19.25 9v6");
}

</style>
