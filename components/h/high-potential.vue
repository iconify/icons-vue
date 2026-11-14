<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpcwb5cdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:high-potential" /></template>
<style>
.cpcwb5cdo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.911 5.215l.309.685a1.5 1.5 0 0 0 1.203.874l.747.082a.726.726 0 0 1 .409 1.258l-.556.505a1.5 1.5 0 0 0-.46 1.414l.153.736a.726.726 0 0 1-1.07.777l-.653-.372a1.5 1.5 0 0 0-1.486 0l-.653.372a.726.726 0 0 1-1.07-.777l.153-.736a1.5 1.5 0 0 0-.46-1.414l-.556-.505a.726.726 0 0 1 .409-1.258l.747-.082A1.5 1.5 0 0 0 15.28 5.9l.309-.685a.726.726 0 0 1 1.322 0M2.5 20.5l5-5l3 2.5l3.5-3.5");
}

</style>
