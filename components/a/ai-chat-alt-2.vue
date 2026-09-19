<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="w5un1bcyv"/><ellipse transform="rotate(-60 24 24)" class="w5un1bcyv"/><ellipse transform="rotate(-30 24 24)" class="vb_vbgbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ai-chat-alt-2" /></template>
<style>
.vb_vbgbqn {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 20.5px;
  ry: 7.5px;
}

.w5un1bcyv {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.5px;
  ry: 20.5px;
}

</style>
