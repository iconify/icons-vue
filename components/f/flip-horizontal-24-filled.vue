<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x287q0bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-horizontal-24-filled" /></template>
<style>
.x287q0bza {
  fill: currentColor;
  d: path("M21.837 19.547A1 1 0 0 1 21 20h-7a1 1 0 0 1-1-1V3a1 1 0 0 1 1.916-.4l7 16a1 1 0 0 1-.08.947M15 7.781V18h4.471zM2.5 20a.5.5 0 0 1-.452-.713l8-17A.5.5 0 0 1 11 2.5v17a.5.5 0 0 1-.5.5z");
}

</style>
