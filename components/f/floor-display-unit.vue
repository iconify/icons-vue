<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvg8h1o9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floor-display-unit" /></template>
<style>
.vvg8h1o9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5h15.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75H4.25A1.75 1.75 0 0 1 2.5 5.75v-1.5A1.75 1.75 0 0 1 4.25 2.5m1.25 5v14m13-14v14M8 5h8M5.5 12.5h13M5.5 17h13m-13 4.5h13M8.875 9.75h.75A1.375 1.375 0 0 1 11 11.125A1.375 1.375 0 0 1 9.625 12.5h-.75A1.375 1.375 0 0 1 7.5 11.125A1.375 1.375 0 0 1 8.875 9.75m5.5 0h.75a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-.75A1.375 1.375 0 0 1 13 11.125a1.375 1.375 0 0 1 1.375-1.375m-5.5 4.5h.75A1.375 1.375 0 0 1 11 15.625A1.375 1.375 0 0 1 9.625 17h-.75A1.375 1.375 0 0 1 7.5 15.625a1.375 1.375 0 0 1 1.375-1.375m5.5 0h.75a1.375 1.375 0 0 1 1.375 1.375A1.375 1.375 0 0 1 15.125 17h-.75A1.375 1.375 0 0 1 13 15.625a1.375 1.375 0 0 1 1.375-1.375m-5.5 4.5h.75A1.375 1.375 0 0 1 11 20.125A1.375 1.375 0 0 1 9.625 21.5h-.75A1.375 1.375 0 0 1 7.5 20.125a1.375 1.375 0 0 1 1.375-1.375m5.5 0h.75a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-.75A1.375 1.375 0 0 1 13 20.125a1.375 1.375 0 0 1 1.375-1.375");
}

</style>
