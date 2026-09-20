<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="wtqp2fzjk"/><circle class="uo6juyzuz"/><path class="px8xs5d3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hadi" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.px8xs5d3n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.731 20.311v6.626m-9.88-2.5a2.5 2.5 0 1 1-5 0V22.81a2.5 2.5 0 1 1 5 0m0 4.127v-6.626m7.378 2.5a2.5 2.5 0 1 0-5 0v1.625a2.5 2.5 0 1 0 5 0m0 2.501V16.936");
}

.uo6juyzuz {
  cx: 34.731px;
  cy: 17.249px;
  r: 0.75px;
  fill: currentColor;
}

.wtqp2fzjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.533 29.464c.39.656.952 1.207 1.614 1.584s1.424.579 2.187.579s1.524-.202 2.186-.579a4.45 4.45 0 0 0 1.615-1.584M12.394 16.936v10.001m0-4.126a2.5 2.5 0 1 1 5 0v4.126");
}

</style>
