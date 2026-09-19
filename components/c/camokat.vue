<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rfux-xbit"/><circle class="s3310misf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:camokat" /></template>
<style>
.rfux-xbit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 25.964c0 8.6-6.972 15.572-15.572 15.572s-15.572-6.972-15.572-15.572H4.5c0-10.77 8.73-19.5 19.5-19.5s19.5 8.73 19.5 19.5");
}

.s3310misf {
  cx: 27.928px;
  cy: 25.964px;
  r: 6.599px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
