<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="stefssw6c"/><path class="bp-vp2sxz"/><ellipse class="mrm18eb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bubble" /></template>
<style>
.bp-vp2sxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.084 24a21.4 21.4 0 0 0-2.596-10.25m.137 20.216A21.4 21.4 0 0 0 38.084 24m-28.168-.284a21.4 21.4 0 0 0 2.596 10.25m-.137-20.216a21.4 21.4 0 0 0-2.459 9.966");
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

.mrm18eb7w {
  cx: 24px;
  cy: 17.225px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.36px;
  ry: 3.475px;
}

.stefssw6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 0 0 5.096 13.75h37.808A21.5 21.5 0 0 0 24 2.5m0 43a21.49 21.49 0 0 0 19.041-11.534H4.96A21.49 21.49 0 0 0 24 45.5m18.904-31.75H5.096a21.48 21.48 0 0 0-.137 20.216H43.04a21.48 21.48 0 0 0-.137-20.216");
}

</style>
