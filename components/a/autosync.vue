<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="e0wfll4ki"/><circle class="b6zjh9b1x"/><path class="pkia3ob0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:autosync" /></template>
<style>
.b6zjh9b1x {
  cx: 24px;
  cy: 24px;
  r: 5.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

.e0wfll4ki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11.383c6.968 0 12.617 5.649 12.617 12.617S30.968 36.617 24 36.617S11.383 30.968 11.383 24c0-6.802 5.382-12.346 12.12-12.607q.247-.01.497-.01");
}

.pkia3ob0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.604 23.422c2.62-.143 5.258-.254 8.835 2.207M11.39 24.445c-2.619.143-5.242.258-8.82-2.203m21.956 14.365c.143 2.62.22 5.248-2.24 8.826m1.217-34.04c-.143-2.62-.259-5.249 2.203-8.826");
}

</style>
