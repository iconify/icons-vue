<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="af1yqetlh"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bnh-bemobile" /></template>
<style>
.af1yqetlh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.779 20.997l12.94-8.171l6.234 6.09m.269 3.284l9.723-6.4l7.259 6.145M5.507 38.05H42.5M5.945 30.498H42.5M31.307 15.977s-2.877-2.762-8.008-1.652M42.5 24.515c-.176.452-.486.851-.881 1.133s-.872.447-1.357.468a2.54 2.54 0 0 1-1.553-.453a2.6 2.6 0 0 1-1.354.446a2.6 2.6 0 0 1-1.553-.452a2.6 2.6 0 0 1-1.355.446a2.6 2.6 0 0 1-1.553-.453a2.6 2.6 0 0 1-1.354.446a2.6 2.6 0 0 1-1.553-.453a2.6 2.6 0 0 1-1.354.446a2.6 2.6 0 0 1-1.553-.453a2.6 2.6 0 0 1-1.355.446a2.6 2.6 0 0 1-1.553-.453a2.6 2.6 0 0 1-1.354.446a2.6 2.6 0 0 1-1.553-.453a2.6 2.6 0 0 1-1.354.446a2.6 2.6 0 0 1-1.553-.453a2.6 2.6 0 0 1-1.354.446a2.6 2.6 0 0 1-1.554-.453a2.6 2.6 0 0 1-1.354.446a2.6 2.6 0 0 1-1.553-.453a2.6 2.6 0 0 1-1.354.446a2.6 2.6 0 0 1-1.553-.452v0a2.9 2.9 0 0 1-1.354.447a2.94 2.94 0 0 1-1.619-.357c-.49-.27-.9-.686-1.163-1.18");
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
