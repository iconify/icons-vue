<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xkpbt7uga"/><path class="lvvlc6bzr"/><path class="rf9svqbrk"/><circle class="u_6ap34my"/><path class="govei7beq"/><path class="sg9mfvbwq"/><path class="q5c3_wbby"/><path class="a-tjgob8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blind" /></template>
<style>
.a-tjgob8y {
  fill: currentColor;
  d: path("M25.3 30.1c.15.15.15.3.15.45c0 .45-.3.75-.75.75s-.75-.3-.75-.75c0-.15 0-.3.15-.45");
}

.govei7beq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.8 24c1.1 1.9 1.8 4.2 1.8 6.6c0 7.1-5.8 12.9-12.9 12.9c-.8 0-1.5-.1-2.3-.2");
}

.lvvlc6bzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.4 8.6c.7-.2 1.5-.3 2.3-.3c5 0 9 4.1 9 9s-4.1 9-9 9c-.8 0-1.5-.1-2.3-.3");
}

.q5c3_wbby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.2 29.5c.1.3.1.7.1 1.1c0 2.5-2.1 4.6-4.6 4.6c-.8 0-1.6-.2-2.3-.6");
}

.rf9svqbrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.4 13.4c.7-.4 1.4-.6 2.3-.6c2.5 0 4.6 2.1 4.6 4.6S27.2 22 24.7 22c-.8 0-1.6-.2-2.3-.6");
}

.sg9mfvbwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.1 27.2c.4 1 .7 2.2.7 3.4c0 5-4.1 9-9 9c-.8 0-1.5-.1-2.3-.3");
}

.u_6ap34my {
  cx: 24.7px;
  cy: 17.4px;
  r: 0.75px;
  fill: currentColor;
}

.xkpbt7uga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.4 4.5h12v39h-12zm3.7 39v-39m4.6 0v39m3.7-38.8c.7-.1 1.5-.2 2.3-.2c7.1 0 12.9 5.8 12.9 12.9s-5.8 12.9-12.9 12.9c-.8 0-1.5-.1-2.3-.2");
}

</style>
