<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bn4cd6iwp"/><path class="i4pafkbdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:daily-deal" /></template>
<style>
.bn4cd6iwp {
  d: path("M12.828 21H6q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T4 19V5l2-1.5L8 5l2-1.5L12 5l2-1.5L16 5l2-1.5L20 5v5.7M4 8.5h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4pafkbdy {
  d: path("M8.75 11.5h.5A1.75 1.75 0 0 1 11 13.25v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 7 13.75v-.5a1.75 1.75 0 0 1 1.75-1.75m5.811 5.189l2.75-2.75a1.5 1.5 0 0 1 1.06-.439H20.5A1.5 1.5 0 0 1 22 15v2.129a1.5 1.5 0 0 1-.439 1.06l-2.75 2.75a1.5 1.5 0 0 1-2.122 0l-2.128-2.128a1.5 1.5 0 0 1 0-2.122m5.189-.939h.01");
}

</style>
