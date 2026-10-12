<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5_i7-6fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:daytime-running-lights-sharp" /></template>
<style>
.u5_i7-6fj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5.5c-3.9 0-7 2.9-7 6.5s3.1 6.5 7 6.5h1.75v-13zm-2.5 4v5m7.55-7.8l3.01-3.01m-1.38 5.44l3.93-1.63M17 12h4.25m-4.82 2.87l3.93 1.63m-5.56.8l3.01 3.01");
}

</style>
