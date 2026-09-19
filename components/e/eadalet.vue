<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ahd7y-b7k"/><circle class="cpk0fnbgt"/><path class="r7m0cdcbw"/><path class="y25dmwb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eadalet" /></template>
<style>
.ahd7y-b7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.319 31.292a4.12 4.12 0 0 0 3.818-2.574l-7.637.001a4.12 4.12 0 0 0 3.819 2.573m-.002-14.13a.918.918 0 1 0-.001-1.836a.918.918 0 0 0 0 1.836m14.98-.002a.919.919 0 1 0-.001-1.838a.919.919 0 0 0 .001 1.838m.002 14.129a4.12 4.12 0 0 0 3.819-2.574l-7.638.001a4.12 4.12 0 0 0 3.82 2.573");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r7m0cdcbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.857 30.406l2.442.012m-1.245-13.015V33.81c0 .415 1.245-.088 1.245-.088m-.615-21.917c-.569 1.038-1.633 1.68-2.786 1.68c-1.769 0-3.203-1.485-3.203-3.316h0c0-1.831 1.434-3.316 3.203-3.316h0c1.149 0 2.21.637 2.78 1.668m-7.26 7.722l12.96-.002m-14.061 1.031L13.58 28.538m5.477-.001l-2.74-11.265m14.979-.112l-2.737 11.266m5.477-.001l-2.74-11.265M10.873 32.121s3.439-.418 7.022.8c2.742.933 4.905 3.391 4.905 3.391m14.284-4.191s-3.438-.418-7.022.8c-2.742.933-4.905 3.391-4.905 3.391m-14.455-1.573c2.493-.536 6.01-.17 7.764.402c2.257.737 4 2.255 4.882 3.03m13.908-3.432c-2.494-.536-6.01-.17-7.765.403c-2.257.736-4 2.254-4.882 3.03");
}

.y25dmwb_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.025 37.611s1.057-.458 2.579-.798s3.509-.563 4.718-.335c1.133.213 2.814 1.18 4.114 1.969c.907.55 2.543 1.914 2.543 1.914m13.954-2.75s-1.057-.458-2.579-.798s-3.509-.563-4.718-.335c-1.133.213-2.815 1.18-4.114 1.969c-.907.55-2.543 1.914-2.543 1.914m1.864-30.192l1.646-.01l-.5-1.568l.518 1.562l1.337-.96l-1.325.976l1.325.975l-1.337-.96l-.518 1.563l.5-1.568z");
}

</style>
