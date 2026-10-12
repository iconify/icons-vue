<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgsdblekx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:linter-sharp" /></template>
<style>
.hgsdblekx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h11.5m-11.5 5h18.5m-18.5 5h13m-13 5l1.625-1.95L6 19.75l1.625 1.95l1.625-1.95l1.625-1.95l1.625 1.95l1.625 1.95l1.625-1.95");
}

</style>
