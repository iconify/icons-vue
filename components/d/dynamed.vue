<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="qi-9sinur"/><path class="t7jzsdmuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dynamed" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.qi-9sinur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.924 22.014V15.5h1.466a2.85 2.85 0 0 1 2.85 2.85v.814a2.85 2.85 0 0 1-2.85 2.85zm14.852 0v-2.687a1.628 1.628 0 1 0-3.257 0m0 2.687v-4.316m-2.043 2.687v2.199a1.628 1.628 0 0 1-2.78 1.151");
}

.t7jzsdmuj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.476 17.698v2.687a1.628 1.628 0 1 1-3.257 0v-2.687m13.857 2.687a1.628 1.628 0 1 1-3.257 0v-1.058a1.628 1.628 0 1 1 3.257 0m0 2.687v-4.316m-18.59 14.795v-6.507l3.256 6.514l3.257-6.504V32.5m5.086-.823a1.628 1.628 0 0 1-3.043-.807v-1.058a1.628 1.628 0 1 1 3.257 0v.529H24.04m8.475-.528a1.628 1.628 0 0 0-3.257 0v1.059a1.628 1.628 0 0 0 3.257 0m-.001 1.628v-6.514");
}

</style>
