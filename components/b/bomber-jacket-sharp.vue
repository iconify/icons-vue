<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hcxlphbxm"/><path class="cfwwefjkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bomber-jacket-sharp" /></template>
<style>
.cfwwefjkb {
  d: path("m9.75 3.5l2.25 5l2.25-5M12 8.5v12.25");
}

.hcxlphbxm {
  d: path("M9.75 3.25h4.5l4.5 1l2.5.55v14.7h-3v-12h-3v13.25h-6.5V7.5h-3v12h-3V4.8l2.5-.55Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
