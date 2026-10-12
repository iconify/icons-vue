<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofup5ybox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:body-lotion-sharp" /></template>
<style>
.ofup5ybox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8V2.75m-2.5 0h5.25M2.75 8h9.5v13.25h-9.5zm2.75 7.5h4m4.25 5.75h6.5l.565-2.4l-2.415-.5A2.4 2.4 0 0 0 15.5 16c-1.15.85-1.75 2.75-1.75 5.25Z");
}

</style>
