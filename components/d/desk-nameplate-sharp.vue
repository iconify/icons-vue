<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adqmveiej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:desk-nameplate-sharp" /></template>
<style>
.adqmveiej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7.75H19.5l.18 1.24l1.39 9.52l.18 1.24H2.75l.18-1.24l1.39-9.52l.18-1.24zM7.5 12.5h9m-7 3.25h5");
}

</style>
