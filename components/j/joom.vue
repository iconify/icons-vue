<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="b4c-4tb4i"/><path class="tvtg0uztd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:joom" /></template>
<style>
.b4c-4tb4i {
  cx: 16.227px;
  cy: 38.027px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.433px;
  ry: 5.414px;
}

.tvtg0uztd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.621 43.5V16.89c0-7.758 6.855-12.266 11.551-12.39l.034 26.813c.012 9.423-8.289 12.18-11.585 12.187");
}

</style>
