<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tjx5e6b1a"/><g class="y9tr6bcfx"><circle class="st4s9zuej"/><path class="odixsxcpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fermata" /></template>
<style>
.odixsxcpf {
  d: path("M29.418 25.643c0-9.802-17-9.807-17 0c5.611-5.485 11.433-5.567 17 0");
}

.st4s9zuej {
  cx: 20.966px;
  cy: 26.952px;
  r: 2.615px;
}

.tjx5e6b1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.45 38.432V9.566m5.894-3.4l24.994 14.431m0 6.807l-24.994 14.43M7.45 9.566c0-3.4 2.952-5.098 5.894-3.4M7.45 38.432c0 3.398 2.95 5.101 5.894 3.402m24.994-14.43c2.95-1.703 2.95-5.103 0-6.806");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
