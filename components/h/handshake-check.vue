<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6c5vpgzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:handshake-check" /></template>
<style>
.e6c5vpgzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h5l3-2H14l3.5 2.5h4m-19 6H6l4.5 3H13l1.433-1.075m.4-.3L17 12.5h3.292M5 6v6.5m14-6v6m-10.5-4l3 3M12 7l3 3m-.25 8l2 2L21 15.75");
}

</style>
