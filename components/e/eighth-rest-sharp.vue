<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbsprjb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eighth-rest-sharp" /></template>
<style>
.lbsprjb6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.25 2.75l4 4.75l-3.5 4l4 4.5m0 0c-2.5-1-5.5-.25-5 2.25l.317 1.713l1.683 1.287");
}

</style>
