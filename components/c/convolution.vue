<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ajdaxebjd"/><rect class="wc8iu3btr"/><path class="vxegwhbjl"/><rect class="e2rclrsmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:convolution" /></template>
<style>
.ajdaxebjd {
  width: 13px;
  height: 13px;
  x: 2.75px;
  y: 8.25px;
  rx: 2.5px;
}

.e2rclrsmn {
  width: 4.5px;
  height: 4.5px;
  x: 16.75px;
  y: 2.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vxegwhbjl {
  d: path("m10.5 11l6.25-4");
}

.wc8iu3btr {
  width: 5px;
  height: 5px;
  x: 5.5px;
  y: 11px;
  rx: 1px;
}

</style>
