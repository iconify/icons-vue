<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="es5m18bvs"/><path class="aqdswjbcj"/><path class="ejugx5z3a"/></g><circle class="l6cd208_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flow" /></template>
<style>
.aqdswjbcj {
  d: path("m14.94 30.037l8.853-8.933a3.11 3.11 0 0 1 4.418 0l.186.187a3.117 3.117 0 0 1 0 4.417l-8.853 8.933z");
}

.ejugx5z3a {
  d: path("m24.147 30.037l2.418 2.442a3.12 3.12 0 0 1 0 4.417l-.186.186a3.117 3.117 0 0 1-4.418 0l-2.418-2.441z");
}

.es5m18bvs {
  d: path("M12.545 27.642a3.117 3.117 0 0 1 0-4.417l12.307-12.307a3.117 3.117 0 0 1 4.417 0l.186.186a3.117 3.117 0 0 1 0 4.417l-12.16 12.16l-2.355 2.356l-2.353-2.353z");
}

.l6cd208_p {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
