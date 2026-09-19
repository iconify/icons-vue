<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="t53f11bbd"/><path class="wfvotvbuf"/><path class="ndourwinm"/><path class="r9wrerbel"/><circle class="uis2st4qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jiopos-lite" /></template>
<style>
.ndourwinm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.457 19.228a3.485 3.485 0 1 0 6.97 0L33.519 8.61H14.482l-7.91 10.618a3.485 3.485 0 1 0 6.972 0");
}

.r9wrerbel {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.486 19.228a3.485 3.485 0 1 0 6.97 0L30.033 8.61m-3.915 0l1.367 10.618a3.485 3.485 0 1 1-6.97 0L21.882 8.61m11.073 0v-1.5c0-.889-.72-1.609-1.609-1.609H16.654c-.889 0-1.61.72-1.61 1.609v1.5");
}

.t53f11bbd {
  width: 9.33px;
  height: 16.838px;
  x: 19.576px;
  y: 25.662px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.099px;
  ry: 1.099px;
}

.uis2st4qd {
  cx: 24.241px;
  cy: 39.908px;
  r: 0.75px;
  fill: currentColor;
}

.wfvotvbuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.576 38.425h-7.748a3.415 3.415 0 0 1-3.405-3.405V22.297m31.155.13V35.02a3.415 3.415 0 0 1-3.406 3.405h-7.265m-8.392-19.197a3.485 3.485 0 1 1-6.971 0L17.967 8.61");
}

</style>
