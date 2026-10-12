<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo0xobx6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:artboards-lock-sharp" /></template>
<style>
.oo0xobx6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.25h14v11h-14zm0-3.75h6m8-.75v1.5m3 3h1.5m-1.5 11h1.5m-4.5 3v-1.5");
}

</style>
