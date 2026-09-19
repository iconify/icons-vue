<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d9f2h5bzk"/><circle class="giomy471q"/><path class="xpb0rczuw"/><circle class="rw7ipc5sk"/><path class="s_u6w1bwv"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:district" /></template>
<style>
.d9f2h5bzk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.21 24.914c0-1.092.884-1.977 1.976-1.977h0m-1.977 0v5.239");
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

.rw7ipc5sk {
  cx: 30.034px;
  cy: 20.516px;
  r: 0.75px;
  fill: currentColor;
}

.s_u6w1bwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.034 22.937v5.239m-13.266-.442c.361.303.75.442 1.626.442h.443c.722 0 1.307-.586 1.307-1.31h0c0-.723-.585-1.31-1.307-1.31h-.887a1.31 1.31 0 0 1-1.306-1.309h0c0-.723.585-1.31 1.306-1.31h.444c.875 0 1.265.14 1.626.442m2.919-2.072v5.88c0 .547.442.99.988.99h.297m-2.323-5.24h2.076m14.238-1.63v5.88c0 .547.443.99.989.99h.296m-2.323-5.24h2.076m-3.586 4.243c-.34.595-.982.996-1.717.996h0a1.977 1.977 0 0 1-1.976-1.977v-1.285c0-1.092.885-1.977 1.976-1.977h0c.734 0 1.374.4 1.715.993m-23.211.984a1.977 1.977 0 0 0-1.977-1.977h0A1.977 1.977 0 0 0 8.5 24.914V26.2c0 1.092.885 1.977 1.977 1.977h0a1.977 1.977 0 0 0 1.977-1.977m0 1.976v-7.907");
}

.xpb0rczuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.625 22.937v5.239");
}

</style>
