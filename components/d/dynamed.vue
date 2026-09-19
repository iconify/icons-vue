<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="n4lz21gxe"/><path class="cqmyvnbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dynamed" /></template>
<style>
.cqmyvnbod {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.476 17.698v2.687c0 .9-.73 1.629-1.629 1.629h0c-.9 0-1.628-.73-1.628-1.629v-2.687m13.857 2.687c0 .9-.73 1.629-1.628 1.629h0c-.9 0-1.629-.73-1.629-1.629v-1.058c0-.9.73-1.629 1.629-1.629h0c.899 0 1.628.73 1.628 1.629m0 2.687v-4.316m-18.59 14.795v-6.507l3.256 6.514l3.257-6.504V32.5m5.086-.823c-.28.49-.81.822-1.415.822h0c-.9 0-1.629-.73-1.629-1.629v-1.058c0-.9.73-1.629 1.629-1.629h0c.9 0 1.628.73 1.628 1.629v.529h-3.257m8.474-.528c0-.9-.73-1.628-1.629-1.628h0c-.9 0-1.628.729-1.628 1.628v1.059c0 .899.729 1.628 1.628 1.628h0c.9 0 1.629-.73 1.629-1.628m-.001 1.628v-6.514");
}

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

.n4lz21gxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.924 22.014V15.5h1.466a2.85 2.85 0 0 1 2.85 2.85v.814a2.85 2.85 0 0 1-2.85 2.85zm14.852 0v-2.687c0-.9-.73-1.629-1.629-1.629h0c-.9 0-1.628.73-1.628 1.629m0 2.687v-4.316m-2.043 2.687v2.199c0 .9-.73 1.628-1.629 1.628h0a1.62 1.62 0 0 1-1.151-.477");
}

</style>
