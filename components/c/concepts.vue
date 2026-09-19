<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="bpdmqfb2a"/><path class="bupts9yof"/><path class="evqa-fbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:concepts" /></template>
<style>
.bpdmqfb2a {
  cx: 37.008px;
  cy: 8.308px;
  r: 3.599px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.bupts9yof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.337 42.804A20.393 20.393 0 1 1 34.09 6.201m7.31 25.633l1.222.794m-4.018 4.012l1.142.985m-5.436 2.757l.788 1.025m-6.077 1.313l.404 1.253m-5.712-.636l-.04 1.194m-5.515-1.791l-.275 1.188M45.5 27.264h-5.438l-4.964-1.497l.079-4.097l4.885-1.497H45.5");
}

.evqa-fbpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.098 25.767l-5.515-2.127l5.594-1.97");
}

</style>
