<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbiovpbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:boom-barrier-sharp" /></template>
<style>
.dbiovpbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.5h4.5v14.75h-4.5zm4.5 2h14v3.75h-14zm4.25 0l-1.75 3.75M15.5 8.5l-1.75 3.75M19.5 8.5l-1.75 3.75");
}

</style>
