<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9pu5-o9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aircraft-spare-parts" /></template>
<style>
.l9pu5-o9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 11.5l2.5 3h14l2.5-3M5 14.5v7h14v-7m-3.22-8.573l.258.086A1.04 1.04 0 0 1 16.75 7a1.04 1.04 0 0 1-.712.987l-.258.086a1.35 1.35 0 0 0-.78.677l-.032.064a1.5 1.5 0 0 0-.138.917l.045.269a1.03 1.03 0 0 1-.555 1.09l-.188.094A.98.98 0 0 1 13 11l-.146-.146A1.2 1.2 0 0 0 12 10.5a1.2 1.2 0 0 0-.854.354L11 11a.98.98 0 0 1-1.132.184l-.188-.094A1.03 1.03 0 0 1 9.125 10l.045-.269a1.5 1.5 0 0 0-.138-.917L9 8.75a1.35 1.35 0 0 0-.78-.677l-.258-.086A1.04 1.04 0 0 1 7.25 7a1.04 1.04 0 0 1 .712-.987l.258-.086A1.35 1.35 0 0 0 9 5.25l.032-.064a1.5 1.5 0 0 0 .138-.917L9.125 4a1.03 1.03 0 0 1 .555-1.09l.188-.094A.98.98 0 0 1 11 3l.146.146A1.2 1.2 0 0 0 12 3.5a1.2 1.2 0 0 0 .854-.354L13 3a.98.98 0 0 1 1.132-.184l.188.094A1.03 1.03 0 0 1 14.875 4l-.045.269a1.5 1.5 0 0 0 .138.917L15 5.25a1.35 1.35 0 0 0 .78.677M12 7h.01");
}

</style>
