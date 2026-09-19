<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z8fs827lt"/><path class="ry9vhab7s"/><path class="hrkb8eb2t"/><circle class="yixft56xr"/><path class="qjy287bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:exif-pro" /></template>
<style>
.hrkb8eb2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.004 33.203l6.888-9.352a2.84 2.84 0 0 1 4.578.01l6.432 8.806M11.39 26.983l4.299-2.698a1.7 1.7 0 0 1 2.238.383l.707.89");
}

.qjy287bks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.919 9.732a4.07 4.07 0 0 0-3.366 4.673v0c.513 3.146 4.197 6.432 5.153 7.23a.25.25 0 0 0 .353-.032l.02-.028c.642-1.063 3.025-5.332 2.513-8.478a4.07 4.07 0 0 0-4.673-3.365m.894 5.496a1.772 1.772 0 1 1 1.465-2.034h0v.004c.155.965-.5 1.873-1.465 2.03");
}

.ry9vhab7s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.494 32.416l.173 1.992a1.32 1.32 0 0 1-1.206 1.432L9.24 38.316a1.313 1.313 0 0 1-1.433-1.206L6.484 21.488a1.32 1.32 0 0 1 1.206-1.432l.29-.021");
}

.yixft56xr {
  cx: 37.543px;
  cy: 19.502px;
  r: 2.785px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z8fs827lt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.168 19.54l.01.226l.356 12.155a1.324 1.324 0 0 0 1.367 1.281l26.593-.786l2.724-.086a1.324 1.324 0 0 0 1.281-1.367l-.463-15.677a1.33 1.33 0 0 0-1.367-1.28l-29.059.871");
}

</style>
