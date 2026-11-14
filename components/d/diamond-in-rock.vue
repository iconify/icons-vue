<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xbie-fu3p"/><path class="jj-_zb5zi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diamond-in-rock" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jj-_zb5zi {
  d: path("m8.226 9.093l.824-1.03a1.5 1.5 0 0 1 1.171-.563h3.558a1.5 1.5 0 0 1 1.171.563l.824 1.03a1.5 1.5 0 0 1 .029 1.837L13.2 14.4a1.5 1.5 0 0 1-2.4 0l-2.603-3.47a1.5 1.5 0 0 1 .029-1.837M7.5 10h9");
}

.xbie-fu3p {
  d: path("m2.71 11.411l2.03-5.682a1.75 1.75 0 0 1 .975-1.027l4.72-1.967a1.75 1.75 0 0 1 1.154-.067l5.701 1.629a1.75 1.75 0 0 1 1.06.853l2.809 5.217a1.75 1.75 0 0 1 .138 1.323l-2.025 6.886a1.75 1.75 0 0 1-1.198 1.189l-5.534 1.581a1.75 1.75 0 0 1-1.069-.035l-5.69-2.032a1.75 1.75 0 0 1-1.06-1.06l-2.011-5.63a1.75 1.75 0 0 1 0-1.178");
}

</style>
