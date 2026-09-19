<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dl3sk5bkg"/><circle class="qk9jedcyo"/><path class="u0tgipb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alarmcom" /></template>
<style>
.dl3sk5bkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 30.094V17.906a4 4 0 0 0-2.372-3.654L26.326 7.655a5.7 5.7 0 0 0-4.652 0L6.872 14.252A4 4 0 0 0 4.5 17.906v12.188a4 4 0 0 0 2.372 3.654l14.802 6.597c1.48.66 3.172.66 4.652 0l14.802-6.597a4 4 0 0 0 2.372-3.654");
}

.qk9jedcyo {
  cx: 33.502px;
  cy: 17.184px;
  r: 2.218px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u0tgipb_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.242 28.398L24 16.445L12.759 28.398");
}

</style>
