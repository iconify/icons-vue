<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="xav3-zbdm"/><path class="b5h3urv6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gear-vpn" /></template>
<style>
.b5h3urv6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30 24.087h15.5m-15.363-12.67a14 14 0 0 1 4.46 3.435m.128 18.147a14 14 0 0 1-4.588 3.584M16.375 12.259a14 14 0 0 1 8.845-2.206M10.007 24.44a14 14 0 0 1 2.483-8.41m5.154 20.444a14 14 0 0 1-6.434-6.78m12.567 6.003V45.5m10.948-12.501l6.548 3.804M11.21 29.694l-6.27 4.254m7.55-17.918l-6.394-3.933m19.124-2.044l.08-7.514m9.298 12.313l6.459-3.94");
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

.xav3-zbdm {
  cx: 24px;
  cy: 24px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
