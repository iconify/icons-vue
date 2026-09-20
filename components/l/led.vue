<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm9uzjeuh"/><path class="uph7_3b8e"/><path class="f7vggsb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:led" /></template>
<style>
.f7vggsb6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.342 19.273v9.4h4.13M20.787 24h2.719m1.451 4.741h-4.17V19.26h4.17m3.609 9.562v-9.644h2.043c2.194 0 3.973 1.889 3.973 4.22v1.205c0 2.33-1.779 4.22-3.973 4.22z");
}

.uph7_3b8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.17 24c0 8.378-6.792 15.17-15.17 15.17S8.83 32.378 8.83 24S15.622 8.83 24 8.83S39.17 15.622 39.17 24m0 0h6.33m-43 0h6.33m22.756-13.139l3.164-5.48M13.25 42.62l3.164-5.481m15.172 0l3.164 5.48M13.25 5.38l3.164 5.481");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
