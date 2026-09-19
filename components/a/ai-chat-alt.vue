<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="suyzbibao"/><path class="c5woa9bbc"/><circle class="wzg4aubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ai-chat-alt" /></template>
<style>
.c5woa9bbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.295 20.394l5.07 2.927a12.81 12.81 0 0 1 6.404 11.091v5.858a5.23 5.23 0 0 0 5.23 5.23h0a5.23 5.23 0 0 0 5.23-5.23v-5.856c0-4.576 2.44-8.804 6.403-11.092l5.073-2.928a5.23 5.23 0 0 0 1.914-7.144h0a5.23 5.23 0 0 0-7.144-1.914l-5.072 2.928a12.81 12.81 0 0 1-12.807 0l-5.072-2.928a5.23 5.23 0 0 0-7.143 1.914h0a5.23 5.23 0 0 0 1.914 7.144");
}

.suyzbibao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.705 27.607l-5.07-2.928a12.81 12.81 0 0 1-6.404-11.091V7.73a5.23 5.23 0 0 0-5.23-5.23h0a5.23 5.23 0 0 0-5.23 5.23v5.856c0 4.576-2.44 8.804-6.403 11.092l-5.073 2.928a5.23 5.23 0 0 0-1.914 7.144h0a5.23 5.23 0 0 0 7.144 1.914l5.072-2.928a12.81 12.81 0 0 1 12.807 0l5.072 2.928a5.23 5.23 0 0 0 7.143-1.914h0a5.23 5.23 0 0 0-1.914-7.144Z");
}

.wzg4aubzr {
  cx: 24px;
  cy: 24px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
