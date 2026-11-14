<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjm3t_97c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:double-bass" /></template>
<style>
.fjm3t_97c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10c-3.5 0-4 1.5-3.25 3.5c.5 1.5-2.75 2-2.75 5c0 2.25 2.5 3 6 3s6-.75 6-3c0-3-3.25-3.5-2.75-5C16 11.5 15.5 10 12 10m0-5v11.5M12 5a1.5 1.5 0 1 1 1.5-1.5");
}

</style>
