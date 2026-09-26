<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b8d0o2bue"/><path class="jpo7_pb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:door-fill" /></template>
<style>
.b8d0o2bue {
  fill: currentColor;
  d: path("M5 22L5 4C5 2.8954 5.8954 2 7 2L17 2C18.1046 2 19 2.8954 19 4L19 22L5 22ZM15 11C15 10.4477 14.5523 10 14 10C13.4477 10 13 10.4477 13 11L13 13C13 13.5523 13.4477 14 14 14C14.5523 14 15 13.5523 15 13L15 11Z");
  stroke: none;
}

.jpo7_pb2a {
  d: path("M2 21L22 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
