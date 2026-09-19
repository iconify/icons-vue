<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wf6r0wbpc"/><path class="fsex701er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:feeel" /></template>
<style>
.fsex701er {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.18 4.5h29.64L20.19 18.59h18.63L14.25 32.03z");
}

.wf6r0wbpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.18 43.5l11.01-24.91L9.18 4.5z");
}

</style>
