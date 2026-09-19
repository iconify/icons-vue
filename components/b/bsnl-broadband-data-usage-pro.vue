<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="mvcls1moz"/><path class="dgb0hsu8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bsnl-broadband-data-usage-pro" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dgb0hsu8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.715 13.416L27.047 29.411l-4.729-4.618v12.989h13.26l-4.465-4.374l13.858-14.147");
}

.mvcls1moz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m3.307 29.834l14.398-14.7l-4.668-4.572h12.95v12.684l-4.41-4.318L5.645 35.194");
}

</style>
