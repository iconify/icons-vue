<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tnsc6ztsj"/><rect transform="matrix(-1 0 0 -1 34.775 48)" class="xdem-_bzz"/><path class="wz7xqzbyc"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:glo-cafe" /></template>
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

.tnsc6ztsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.378 20.037v8.972A2.99 2.99 0 0 1 17.388 32a2.98 2.98 0 0 1-2.115-.876");
}

.wz7xqzbyc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.543 16v10.467c0 .826.67 1.496 1.495 1.496h.449m2.135-4.935a2.99 2.99 0 1 1 5.981 0v1.944a2.99 2.99 0 1 1-5.981 0z");
}

.xdem-_bzz {
  width: 5.981px;
  height: 7.925px;
  x: 14.397px;
  y: 20.037px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.991px;
  ry: 2.991px;
}

</style>
