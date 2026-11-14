<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd01whtec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campaign-active" /></template>
<style>
.dd01whtec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.11 15.999L7 12H3V8h4l8-4.5v11.421M5.5 12l1 5m10.75-9.5a3.5 3.5 0 0 1 0 5m1.75-7q.188.196.359.407t.324.436t.287.461q.133.237.247.484t.206.503t.163.518q.07.262.119.529q.049.268.075.538q.026.271.029.542q.003.272-.016.543t-.061.54t-.106.533t-.15.521t-.193.508t-.235.49t-.275.468M16 19a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>
