<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="duqlzzbjl"/><path class="s7z48ib6u"/><path class="qw3l94b7j"/><circle class="cielmwbmz"/><path class="uvca5acek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:earthmoon" /></template>
<style>
.cielmwbmz {
  cx: 31.953px;
  cy: 13.599px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.duqlzzbjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.1 31.6a21.48 21.48 0 0 0-38.5 3.5");
}

.qw3l94b7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.702 36.089c-.1-1.8.498-2.489-1.102-2.489c-.7 0-1.7 0-2-.5c-.4-1-.8-1-1.5-1.2a3.3 3.3 0 0 0-1.9-.3c-.3.1.3 1.6-.5 1.5c-.4-.1-.9-1.8-1.6-2.3a2.32 2.32 0 0 0-2.5.4c-1.4 1.3-2.3 1.6-3.2 1.1c-.6-.3-.3-2.1.1-2.4c.9-.6 1.3 0 2-1c.2-.3-.3-1 .2-1.9s2.5 0 3.3-1.1s2.8-2.7 4.4-1.6a4.4 4.4 0 0 0 1 .6c.3.2.6-.6 1-1s.6-.3 1.3-.3a19 19 0 0 0 3.55-1.377m-19.01-9.136l-1.333.667l-.667 1.333l-.667-1.333l-1.333-.667l1.333-.667l.667-1.333l.667 1.333Zm27.99 7.709l-1.333.667l-.667 1.333l-.667-1.333l-1.333-.667l1.333-.667l.667-1.333l.667 1.333Z");
}

.s7z48ib6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 42.8c-.5-2.3-.2-3.8 1.7-5.2a3.67 3.67 0 0 0 1.3-1.8a2.1 2.1 0 0 1 1.3-1.3A6.38 6.38 0 0 1 22 34c1.5.6 2.2 1.8 3.4 2.3a3.08 3.08 0 0 0 2.3.1c2.1-1 3.4.2 4.2 1.6a36.5 36.5 0 0 0 3.1 4.3");
}

.uvca5acek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.842 24.451a2 2 0 0 1 3.404-1.857m-1.756-.88l-.154-4.356m-1.645 5.841L9.22 22.058m7.51-.05l2.19-4.216m-5.469 6.673l-4.35 1.043m5.264-3.362l-2.952-3.592m6.568 4.004l3.647-2.685");
}

</style>
