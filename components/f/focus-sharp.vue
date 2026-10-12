<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvjk89bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:focus-sharp" /></template>
<style>
.mvjk89bxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75v-5h5m8.5 0h5v5m0 8.5v5h-5m-8.5 0h-5v-5m6-7.5h6.5v6.5h-6.5z");
}

</style>
