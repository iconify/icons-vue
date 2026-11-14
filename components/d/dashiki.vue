<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ok4wuc4gs"/><path class="nw1z20kkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dashiki" /></template>
<style>
.nw1z20kkx {
  d: path("m8 7l4 5l4-5");
}

.ok4wuc4gs {
  d: path("M9.5 3a2.5 2.5 0 0 0 5 0h7v9h-4v9.5h-11V12h-4V3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
