<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5ip5yzgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:intent-signal" /></template>
<style>
.k5ip5yzgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9 9l11 4l-5 2l-2 5Zm-2.898-.776a3 3 0 0 1 2.122-2.122M2.845 7.915a6.25 6.25 0 0 1 5.07-5.07");
}

</style>
