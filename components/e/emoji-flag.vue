<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="weruj009g"/><path class="k3dg-_b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-flag" /></template>
<style>
.k3dg-_b-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 27.957c-2.459-.636-4.875-1.272-9.75-1.272c-8.478 0-11.022 2.543-19.5 2.543c-4.875 0-7.334-.636-9.75-1.271m39-7.913c-2.459-.636-4.875-1.272-9.75-1.272c-8.478 0-11.022 2.543-19.5 2.543c-4.875 0-7.334-.636-9.75-1.271");
}

.weruj009g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 35.87c2.416.636 4.875 1.271 9.75 1.271c8.478 0 11.022-2.543 19.5-2.543c4.875 0 7.291.636 9.75 1.272V12.13c-2.459-.635-4.875-1.271-9.75-1.271c-8.478 0-11.022 2.543-19.5 2.543c-4.875 0-7.334-.636-9.75-1.271z");
}

</style>
