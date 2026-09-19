<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q_coko5hz"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cifra-club-tuner" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.q_coko5hz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.729 12v16.7A2.73 2.73 0 0 1 24 31.43h0a2.73 2.73 0 0 1-2.729-2.73V12m-4.096 15.202c-.465-.98-.725-2.075-.725-3.231s.26-2.252.725-3.232m13.65.001c.465.98.725 2.075.725 3.23s-.26 2.252-.725 3.232m-17.442 2.221c-.84-1.634-1.316-3.488-1.316-5.452s.475-3.819 1.316-5.453m21.234 0c.84 1.634 1.316 3.488 1.316 5.453s-.475 3.818-1.316 5.453M24 36v-4.571");
}

</style>
