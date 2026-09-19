<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a4pzx531d"/><path class="a7yo55gsc"/><path class="f7vggsb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:led" /></template>
<style>
.a4pzx531d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5h0C12.126 45.5 2.5 35.874 2.5 24q0 0 0 0C2.5 12.126 12.126 2.5 24 2.5h0c11.874 0 21.5 9.626 21.5 21.5");
}

.a7yo55gsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.17 24c0 8.378-6.792 15.17-15.17 15.17S8.83 32.378 8.83 24h0c0-8.378 6.792-15.17 15.17-15.17S39.17 15.622 39.17 24m0 0h6.33m-43 0h6.33m22.756-13.139l3.164-5.48M13.25 42.62l3.164-5.481m15.172 0l3.164 5.48M13.25 5.38l3.164 5.481");
}

.f7vggsb6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.342 19.273v9.4h4.13M20.787 24h2.719m1.451 4.741h-4.17V19.26h4.17m3.609 9.562v-9.644h2.043c2.194 0 3.973 1.889 3.973 4.22v1.205c0 2.33-1.779 4.22-3.973 4.22z");
}

</style>
