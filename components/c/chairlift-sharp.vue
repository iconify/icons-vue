<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af_f6ebxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chairlift-sharp" /></template>
<style>
.af_f6ebxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 6.25l18.5-3.5M7.75 5.3V10m7.5 7v3.5h3M7 10h2.5v3.75H17V17H6v-7z");
}

</style>
