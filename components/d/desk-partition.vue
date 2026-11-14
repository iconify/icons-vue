<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuyl8ebfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:desk-partition" /></template>
<style>
.kuyl8ebfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5h19M4 16.5V21m16-4.5V21M11 3h2v13.5h-2ZM2.5 7h5.75v5H2.5Zm13.25 0h5.75v5h-5.75ZM5.5 12v4.5m13-4.5v4.5");
}

</style>
