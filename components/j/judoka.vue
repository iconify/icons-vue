<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sym--ublt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:judoka" /></template>
<style>
.sym--ublt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5L7.5 4H10l2 5l2-5h2.5L21 9.5L18.5 12l-1-1v10h-11V11l-1 1ZM6.5 15h11M12 15l-2.25 3.25M12 15l2.25 3.25");
}

</style>
