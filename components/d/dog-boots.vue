<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrbwfwyso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-boots" /></template>
<style>
.nrbwfwyso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h4.75V12c3 .5 3.5 3 3.5 5.5v3H2.5Zm11 0h4.75V12c3 .5 3.5 3 3.5 5.5v3H13.5ZM2.5 7h4.75m6.25 0h4.75m-12 9.75h.01m10.99 0h.01");
}

</style>
