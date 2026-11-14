<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v--qkpb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bird-feeder" /></template>
<style>
.v--qkpb2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.5V7m-4.639 3.275l3.774-2.664a1.5 1.5 0 0 1 1.73 0l3.774 2.664A1.5 1.5 0 0 1 15.774 13H8.226a1.5 1.5 0 0 1-.865-2.725M6.5 13v7h11v-7m-14 7h17");
}

</style>
