<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vfnfi2bcy"/><path class="g5syatb-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baseball-field-top" /></template>
<style>
.g5syatb-t {
  d: path("m7.5 17l4.5-4.5l4.5 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfnfi2bcy {
  d: path("M12 21.5L2.5 12a13.5 13.5 0 0 1 19 0Z");
}

</style>
