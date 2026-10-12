<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhce2gbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:celtic-knot-sharp" /></template>
<style>
.rhce2gbgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4a8.66 8.66 0 0 0-1.9 13.29m4.39 2.56a8.66 8.66 0 0 0 6.17-.85m0 0a8.66 8.66 0 0 0-10.55-8.29m-4.42 2.52A8.66 8.66 0 0 0 3.34 19m0 0a8.66 8.66 0 0 0 12.46-4.99m.02-5.09A8.66 8.66 0 0 0 12 4");
}

</style>
