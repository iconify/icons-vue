<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k7ur-sb6x"/><path class="e-1gs2bfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dpad-down" /></template>
<style>
.e-1gs2bfa {
  d: path("m9.5 16.75l2.5 2.5l2.5-2.5");
}

.k7ur-sb6x {
  d: path("M8 2.5h8V8h5.5v8H16v5.5H8V16H2.5V8H8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
