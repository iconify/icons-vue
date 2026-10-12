<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvwe35euu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gondola-lift-sharp" /></template>
<style>
.qvwe35euu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 4.25l18.5 5M6.75 5.33v4.42m10-1.75v5.25m-13-3.5h6v7h-6zm10 3.5h6v7h-6zm-10-.5h6m4 3.5h6");
}

</style>
