<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysulb0bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:high-potential" /></template>
<style>
.ysulb0bqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.25 3.75l1.323 2.93l3.195.352l-2.378 2.163l.652 3.148l-2.792-1.593l-2.792 1.593l.652-3.148l-2.378-2.163l3.195-.352ZM2.5 20.5l5-5l3 2.5l3.5-3.5");
}

</style>
