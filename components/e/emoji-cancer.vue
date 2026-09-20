<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f-8e6obab"/><path class="njmq7xbhb"/><path class="b7naesbox"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-cancer" /></template>
<style>
.b7naesbox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.94 31.994s-8.356 3.69-18.354-2.322");
}

.f-8e6obab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.158 19.86a4.285 4.285 0 1 1-4.286-4.284a4.286 4.286 0 0 1 4.286 4.285");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.njmq7xbhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.06 16.006s8.356-3.69 18.354 2.322m-8.572 9.812a4.285 4.285 0 1 1 8.57 0a4.285 4.285 0 0 1-8.57 0");
}

</style>
