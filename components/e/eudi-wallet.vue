<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z7f1mb75k"/><path class="xvotbzoge"/><circle class="skyou7byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eudi-wallet" /></template>
<style>
.skyou7byk {
  cx: 36.458px;
  cy: 24.171px;
  r: 2.705px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xvotbzoge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.294 29.925h-6.369a5.82 5.82 0 0 1-5.822-5.818v-.004h0a5.82 5.82 0 0 1 5.817-5.823h6.375c.665 0 1.205.54 1.205 1.206v9.234c0 .665-.54 1.205-1.206 1.205");
}

.z7f1mb75k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.469 15.255l-1.028.334m0-1.081v1.081m.635.875l-.635-.875m-1.028-.334l1.028.334m-.636.875l.636-.875m5.365.828l-1.028.334m0-1.081v1.081m.635.875l-.635-.875m-1.028-.334l1.028.334m-.636.875l.636-.875m4.203 2.841l-1.028.334m0-1.081v1.081m.635.875l-.635-.875m-1.029-.334l1.029.334m-.636.875l.636-.875m2.19 4.003l-1.028.334m0-1.081v1.081m.635.875l-.635-.875m-1.028-.334l1.028.334m-.636.875l.636-.875m-.134 4.003l-1.028.334m0-1.081V28.6m.635.875l-.635-.875m-1.029-.334l1.029.334m-.636.875l.636-.875m-2.147 2.841l-1.028.334m0-1.081v1.081m.635.875l-.635-.875m-1.028-.334l1.028.334m-.636.875l.636-.875m-9.702-15.358l1.028.334m0-1.081v1.081m-.636.875l.636-.875m1.028-.334l-1.028.334m.635.875l-.635-.875m-4.203 2.841l1.028.334m0-1.081v1.081m-.636.875l.636-.875m1.028-.334l-1.028.334m.635.875l-.635-.875m-2.19 4.003l1.028.334m0-1.081v1.081m-.636.875l.636-.875m1.028-.334l-1.028.334m.635.875l-.635-.875m.134 4.003l1.028.334m0-1.081V28.6m-.636.875l.636-.875m1.028-.334l-1.028.334m.635.875l-.635-.875m2.147 2.841l1.028.334m0-1.081v1.081m-.636.875l.636-.875m1.028-.334l-1.028.334m.635.875l-.635-.875m5.365.85l-1.028.334m0-1.081v1.081m.635.875l-.635-.875m-1.028-.334l1.028.334m-.636.875l.636-.875m25.01-3.045v5.893a3.946 3.946 0 0 1-3.945 3.947H8.446A3.946 3.946 0 0 1 4.5 35.808V12.193a3.946 3.946 0 0 1 3.945-3.947h30.06a3.946 3.946 0 0 1 3.946 3.946v6.099");
}

</style>
