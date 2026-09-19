<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="l_f49zbzr"/><path class="jq_x8ubxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kura-sushi" /></template>
<style>
.jq_x8ubxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.181 12.5c-1.337 1.224-10.338 7.714-10.338 7.714s9.565 5.396 9.565 6.01M27.32 12.5c2.357 0 7.369 1.65 7.369 1.65s-.762.672-1.754.609m-5.752 1.737c-.333.51-2.05 6.272-2.128 7.115c11.102-11.112 15.545 1.99 5.371 3.125m-5.678 8.753v-6.837h2.238c1.266 0 2.292 1.028 2.292 2.296s-1.026 2.296-2.292 2.296h-2.238m2.239.001l2.239 2.242m-11.358-6.835v4.572a2.265 2.265 0 1 0 4.53 0v-4.572m13.009 4.572h-3.029m-.75 2.265l2.265-6.837l2.265 6.837m-24.315-6.826V35.5m0-2.381l3.675-4.433m0 6.814l-2.812-3.419");
}

.l_f49zbzr {
  width: 37px;
  height: 35px;
  x: 5.5px;
  y: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
