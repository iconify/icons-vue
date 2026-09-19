<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="mr_n4foyj"/><path class="bwv6xqbzd"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kwgt-generic-app" /></template>
<style>
.bwv6xqbzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.004 10.5h-.568a4.547 4.547 0 0 0-4.548 4.547v3.017c0 .16-.067.313-.186.421l-5.141 4.674a1.137 1.137 0 0 0 0 1.682l5.141 4.674c.119.108.186.26.186.42v3.018a4.547 4.547 0 0 0 4.547 4.547h.569a.57.57 0 0 0 .568-.568v-9.05c0-.302-.12-.591-.333-.804l-2.675-2.676a.57.57 0 0 1 0-.804l2.675-2.675c.214-.214.333-.503.333-.804v-9.05a.57.57 0 0 0-.568-.569");
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

.mr_n4foyj {
  width: 5.684px;
  height: 27px;
  x: 14.428px;
  y: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.137px;
  ry: 1.137px;
}

</style>
