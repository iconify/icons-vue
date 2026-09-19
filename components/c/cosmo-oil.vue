<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="f2p97tbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cosmo-oil" /></template>
<style>
.f2p97tbvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.454 9.75A9 19 60 0 1 28.5 27.044A9 19 60 0 1 7.546 28.75A9 19 60 0 1 19.5 11.456A9 19 60 0 1 40.454 9.75M42.5 33.977A47 47 0 0 1 27.855 42.5M5.5 12.022c2.363-2.427 5.08-4.61 8.074-6.522M42.5 23.35c-2.81 3.39-6.612 6.532-10.924 9.021c-9.848 5.686-20.559 7-26.076 3.198m0-16.113c2.859-4.08 7.201-7.941 12.326-10.9a44 44 0 0 1 6.48-3.055");
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

</style>
