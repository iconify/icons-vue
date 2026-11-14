<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcv2-sbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:influencer-media" /></template>
<style>
.jcv2-sbbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0M3 21c0-4 3.25-6.5 7-6.5q.617 0 1.212.089m6.699-.874l.309.685a1.5 1.5 0 0 0 1.203.874l.747.082a.726.726 0 0 1 .409 1.258l-.556.505a1.5 1.5 0 0 0-.46 1.414l.153.736a.726.726 0 0 1-1.07.777l-.653-.372a1.5 1.5 0 0 0-1.486 0l-.653.372a.726.726 0 0 1-1.07-.777l.153-.736a1.5 1.5 0 0 0-.46-1.414l-.556-.505a.726.726 0 0 1 .409-1.258l.747-.082a1.5 1.5 0 0 0 1.203-.874l.309-.685a.726.726 0 0 1 1.322 0");
}

</style>
