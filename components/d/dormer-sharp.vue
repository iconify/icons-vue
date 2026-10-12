<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uw429qbfl"/><path class="xi8gw2bya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dormer-sharp" /></template>
<style>
.uw429qbfl {
  d: path("m2.75 19.25l18.5-5M7 17.4V9.5l.42-.42l4.16-4.16l.42-.42l.42.42l4.16 4.16l.42.42v5.9l-.58.15l-8.84 2.3L7 18z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xi8gw2bya {
  d: path("M10.5 10.5H14V13h-4v-2.5z");
}

</style>
