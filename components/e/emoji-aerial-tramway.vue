<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rc-_nyqyt"/><path class="sa0srsbpq"/><circle class="on_sk7cpe"/><circle class="dbx3007wz"/><circle class="xlxx0vb5v"/><circle class="o7yf5cf0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-aerial-tramway" /></template>
<style>
.dbx3007wz {
  cx: 20.917px;
  cy: 13.578px;
  r: 1.587px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o7yf5cf0f {
  cx: 28.625px;
  cy: 15.122px;
  r: 1.587px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.on_sk7cpe {
  cx: 17.063px;
  cy: 12.806px;
  r: 1.587px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rc-_nyqyt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 10.49l37 7.72m-19.27-3.86v6.176m.77 2.316h4.625v8.492H24zm-6.937 0h4.625v10.036h-4.625z");
}

.sa0srsbpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.063 19.754h11.562V37.51H17.063z");
}

.xlxx0vb5v {
  cx: 24.771px;
  cy: 14.35px;
  r: 1.587px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
