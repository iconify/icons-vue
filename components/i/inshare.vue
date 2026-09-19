<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="pkvykupaj"/><path class="eezjfhb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:inshare" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eezjfhb_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.51 22.137l5.93-3.253h0a4.025 4.025 0 1 0-1.204-2.273h0l-5.886 3.187");
}

.pkvykupaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.398 29.816l-6.205-3.062h0a5.17 5.17 0 1 1 1.276-2.328h0l5.803 2.954h0a5.617 5.617 0 1 1-.874 2.436");
}

</style>
