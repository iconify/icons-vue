<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5fz7980p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:governance" /></template>
<style>
.o5fz7980p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 6l3.772-2.095a1.5 1.5 0 0 1 1.456 0L16.5 6a1.334 1.334 0 0 1-.648 2.5H8.148A1.334 1.334 0 0 1 7.5 6M6 11v7m4-7v7m4-7v7m4-7v7M3.5 20.5h17");
}

</style>
