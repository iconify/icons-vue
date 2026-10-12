<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hmz588b6d"/><path class="xg9znsb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:id-card-gov-sharp" /></template>
<style>
.hmz588b6d {
  d: path("M2.75 5.25h18.5v13.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xg9znsb8x {
  d: path("M5.75 8.25h5v7.5h-5zm10.39.07l.41.91l.14.32l.35.04l.99.1l.35.04l-.26.23l-.75.67l-.26.23l.08.34l.21.98l.07.34l-.3-.17l-.87-.5l-.3-.18l-.3.18l-.87.5l-.3.17l.07-.34l.21-.98l.08-.34l-.26-.23l-.75-.67l-.26-.23l.35-.04l.99-.1l.35-.04l.14-.32l.41-.91L16 8zm-2.39 6.93h4.5");
}

</style>
