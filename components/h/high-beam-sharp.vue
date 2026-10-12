<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn22sbg1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:high-beam-sharp" /></template>
<style>
.fn22sbg1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5.5c-3.9 0-7 2.9-7 6.5s3.1 6.5 7 6.5h1.75v-13zm3.75 0h7.75M13.5 8.75h7.75M13.5 12h7.75m-7.75 3.25h7.75M13.5 18.5h7.75");
}

</style>
