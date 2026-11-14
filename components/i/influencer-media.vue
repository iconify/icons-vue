<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc3rk4b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:influencer-media" /></template>
<style>
.vc3rk4b-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3 21c0-3.186 2.062-5.42 4.795-6.198m9.455-2.552l1.323 2.93l3.195.352l-2.378 2.163l.652 3.148l-2.792-1.593l-2.792 1.593l.652-3.148l-2.378-2.163l3.195-.352Z");
}

</style>
