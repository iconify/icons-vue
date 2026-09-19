<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="we75edbts"/><circle class="tz2hzln-u"/><circle class="f_8gftgqm"/><path class="vvm-lxb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ftp-server" /></template>
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

.f_8gftgqm {
  cx: 29.5px;
  cy: 24.5px;
  r: 0.75px;
  fill: currentColor;
}

.tz2hzln-u {
  cx: 23.8px;
  cy: 29.5px;
  r: 0.75px;
  fill: currentColor;
}

.vvm-lxb_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.4 19.2l.4 3.2m-9 4.4l3.1.7m-6 6.2c-.7.6-.8 1.7-.1 2.4l3.5 3.9l2.5-2.2l-3.5-3.9c-.7-.8-1.7-.8-2.4-.2m18.7-16.6c-.7.6-.8 1.7-.1 2.4l3.5 3.9l2.5-2.2l-3.5-3.9c-.7-.7-1.7-.8-2.4-.2");
}

.we75edbts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.6 21c1-2.4 2.3-4.2 4.1-5.7c2.2-1.9 3.8-2.5 7-3.4l-1.3-4.8c-3.4.4-6.7 1.9-9.5 4.3c-2.3 2-4 4.6-5 7.3zm6.1 2.9c1.8-2.9 4.1-5 7.1-6l-1.2-3.7c-3.2-.2-8.8 4.7-9.5 8zm18.8 1c3.1 3.5 2.6 8.8-1 12s-9 3.1-12.1-.4s-2.7-9 .9-12.2s9.1-2.9 12.2.6M22.9 35.6l12.8-11.4");
}

</style>
