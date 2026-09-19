<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f10hydcri"/><path class="lqur1dbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hotmart" /></template>
<style>
.f10hydcri {
  cx: 23.925px;
  cy: 29.825px;
  r: 5.74px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lqur1dbmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.97 15.22s.76 1.014.17 2.027c-.591 1.013-2.027-.507-2.027-.507s.17-4.896-3.207-6.584c0 0 .169 2.532-1.182 3.377s-4.22-4.39-2.195-9.033c0 0-6.078.929-8.61 12.24c0 0-2.195.17-1.013-3.292c-3.546 5.74-5.994 11.565-5.572 17.39c.507 7.09 6.416 12.662 13.676 12.662s13.253-5.656 13.76-12.747c0 0 1.097-11.227-3.8-15.532");
}

</style>
