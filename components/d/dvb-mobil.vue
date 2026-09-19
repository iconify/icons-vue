<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="nurx-3wcb"/><path class="asbnuacfc"/><circle class="ve10q450u"/><path class="bom8zyb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dvb-mobil" /></template>
<style>
.asbnuacfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.264 30.989c.116-1.105 1.106-2 2.21-2s1.906.895 1.79 2l-.347 3.3");
}

.bom8zyb_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.475 28.989l-.559 5.3m2.843-8l-.843 8M12.067 23.361l1.016-9.65h2.146c2.304 0 3.973 1.89 3.727 4.222l-.127 1.206c-.246 2.332-2.312 4.222-4.616 4.222zm15.201 7.628c.116-1.105 1.106-2 2.21-2s1.906.895 1.79 2l-.137 1.3c-.116 1.105-1.106 2-2.21 2s-1.906-.895-1.79-2m-.211 2l.843-8m6.429-7.753c1.317 0 2.27 1.08 2.13 2.413S35 23.36 33.684 23.36H29.75l1.017-9.65H34.7c1.317 0 2.27 1.08 2.13 2.412s-1.321 2.413-2.638 2.413zm-.005 0h-3.929");
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

.nurx-3wcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.242 13.711l-4.175 9.65l-2.142-9.65m1.55 15.278c1.108 0 1.906.892 1.79 2l-.137 1.3c-.117 1.108-1.103 2-2.211 2s-1.906-.892-1.79-2l.137-1.3c.117-1.108 1.103-2 2.211-2m-12.211 2c.116-1.105 1.106-2 2.21-2s1.906.895 1.79 2l-.347 3.3m-3.442-5.3l-.559 5.3");
}

.ve10q450u {
  cx: 33.733px;
  cy: 26.539px;
  r: 0.7px;
  fill: currentColor;
}

</style>
