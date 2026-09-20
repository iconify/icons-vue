<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j6i8bhuwv"/><circle class="giomy471q"/><path class="xpb0rczuw"/><circle class="rw7ipc5sk"/><path class="gb0cs5bcw"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:district" /></template>
<style>
.gb0cs5bcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.034 22.937v5.239m-13.266-.442c.361.303.75.442 1.626.442h.443c.722 0 1.307-.586 1.307-1.31c0-.723-.585-1.31-1.307-1.31h-.887a1.31 1.31 0 0 1-1.306-1.309c0-.723.585-1.31 1.306-1.31h.444c.875 0 1.265.14 1.626.442m2.919-2.072v5.88c0 .547.442.99.988.99h.297m-2.323-5.24h2.076m14.238-1.63v5.88c0 .547.443.99.989.99h.296m-2.323-5.24h2.076m-3.586 4.243a1.977 1.977 0 0 1-3.693-.981v-1.285a1.976 1.976 0 0 1 3.691-.985m-23.211.985a1.977 1.977 0 0 0-3.954 0V26.2a1.977 1.977 0 1 0 3.954 0m0 1.976v-7.907");
}

.giomy471q {
  cx: 14.625px;
  cy: 20.516px;
  r: 0.75px;
  fill: currentColor;
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

.j6i8bhuwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.21 24.914c0-1.092.884-1.977 1.976-1.977m-1.977 0v5.239");
}

.rw7ipc5sk {
  cx: 30.034px;
  cy: 20.516px;
  r: 0.75px;
  fill: currentColor;
}

.xpb0rczuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.625 22.937v5.239");
}

</style>
