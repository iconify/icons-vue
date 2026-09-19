<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="mpy6f3fxb"/><path class="t9kd9gbdl"/><path class="b7k02wbme"/></g><circle class="q32l2v9_y"/><circle class="u_fgeacdi"/><circle class="ey9hobc4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:homebase-resident" /></template>
<style>
.b7k02wbme {
  d: path("m31.373 18.64l2.038.876c1.471.632 2.398 2.065 2.344 3.62l-.109 3.097m-20.571-3.364L12.578 24.1c-1.453.717-2.359 2.17-2.337 3.747l.064 4.73m14.509-.191l4.166-2.757a4.13 4.13 0 0 1 4.432-.06l4.223 2.626");
}

.ey9hobc4k {
  cx: 23.013px;
  cy: 27.686px;
  r: 0.75px;
  fill: currentColor;
}

.mpy6f3fxb {
  d: path("m18.194 32.276l-.093-12.94c-.012-1.582.868-3.046 2.3-3.826l5.11-2.785c.755-.411 1.712-.156 2.139.57c.131.223.201.474.203.73l.114 12.434");
}

.q32l2v9_y {
  cx: 23.013px;
  cy: 19.958px;
  r: 0.75px;
  fill: currentColor;
}

.t9kd9gbdl {
  d: path("m39.84 36.205l-12.268 6.432a7.84 7.84 0 0 1-7.232-.014L8.103 36.142c-2.235-1.184-3.608-3.365-3.603-5.724l.03-12.913c.007-2.359 1.39-4.535 3.63-5.71l12.268-6.432a7.84 7.84 0 0 1 7.232.014l12.238 6.481c2.234 1.184 3.608 3.366 3.602 5.724l-.03 12.913c-.006 2.359-1.39 4.535-3.63 5.71");
}

.u_fgeacdi {
  cx: 23.013px;
  cy: 23.822px;
  r: 0.75px;
  fill: currentColor;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
