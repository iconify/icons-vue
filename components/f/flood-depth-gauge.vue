<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t678cjb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flood-depth-gauge" /></template>
<style>
.t678cjb2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V16m0-10.5h4.5M12 9h3m-3 3.5h4.5M2.5 16c1.5-1.5 3.25-1.5 4.75 0s3.25 1.5 4.75 0s3.25-1.5 4.75 0s3.25 1.5 4.75 0m-19 4.5C4 19 5.75 19 7.25 20.5s3.25 1.5 4.75 0s3.25-1.5 4.75 0s3.25 1.5 4.75 0");
}

</style>
