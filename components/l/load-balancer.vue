<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b8fr_cfzg"/><path class="x2yyw12ok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:load-balancer" /></template>
<style>
.b8fr_cfzg {
  d: path("M2.5 12h3c2.5 0 2.5-5.25 5-5.25h1.75M5.5 12c2.5 0 2.5 5.25 5 5.25h1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x2yyw12ok {
  d: path("m10.5 4.75l2 2l-2 2m0 6.5l2 2l-2 2m4.75-16h6.5v7h-6.5Zm0 10.5h6.5v7h-6.5Z");
}

</style>
