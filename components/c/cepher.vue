<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dq5-2y55e"/><path class="d-zzp81ou"/><path class="f863k8bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cepher" /></template>
<style>
.d-zzp81ou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.34 16.448a10.42 10.42 0 0 0-3.533 7.633c0 3.55 4.93 10.811 4.93 10.811H4.5m24.35-21.784a2.184 2.184 0 0 0-.956 3.34c.63.775 13.554 14.901 14.455 15.792c1.798 1.78.896 2.652-.477 2.652");
}

.dq5-2y55e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.201 34.892V16.448H6.485A1.762 1.762 0 0 1 6 13.108");
}

.f863k8bvd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.526 34.887c1.84 0 4.115.194 4.115-1.888s-2.767-2.839-2.767-5.03c0-1.452.322-3.96 4.206-6.886m3.324 3.611l5.79-6.697m-.92-4.889a1.726 1.726 0 0 0-.85 2.787c.581.678 2.585 2.489 3.648 3.589c.956.989.013 2.531.013 2.531");
}

</style>
