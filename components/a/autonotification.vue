<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="t238zrbfy"/><path class="r_t0apbfp"/><circle class="opmzw43jn"/><path class="dn4ni2rgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:autonotification" /></template>
<style>
.dn4ni2rgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.408 16.454L17.53 27.929a.665.665 0 0 0 .592.968h11.756a.665.665 0 0 0 .592-.968l-5.878-11.475a.665.665 0 0 0-1.184 0");
}

.opmzw43jn {
  cx: 24px;
  cy: 26.517px;
  r: 0.75px;
  fill: currentColor;
}

.r_t0apbfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m44.345 20.827l-3.55-1.02v.079a17.2 17.2 0 0 0-2.017-4.86l.063.062l1.789-3.23a1.595 1.595 0 0 0-.268-1.9l-2.32-2.32a1.595 1.595 0 0 0-1.9-.268l-3.231 1.79l.06.06a17.2 17.2 0 0 0-4.86-2.015h.082l-1.02-3.55A1.595 1.595 0 0 0 25.64 2.5h-3.28c-.711 0-1.337.471-1.533 1.155l-1.02 3.55h.079a17.2 17.2 0 0 0-4.86 2.017l.063-.063l-3.232-1.789a1.595 1.595 0 0 0-1.9.268l-2.32 2.32a1.595 1.595 0 0 0-.267 1.9l1.79 3.231l.06-.06a17.2 17.2 0 0 0-2.015 4.86v-.082l-3.55 1.02A1.595 1.595 0 0 0 2.5 22.36v3.28c0 .711.471 1.337 1.155 1.533l3.55 1.02v-.079a17.2 17.2 0 0 0 2.017 4.86l-.063-.062l-1.789 3.23a1.595 1.595 0 0 0 .268 1.9l2.32 2.32a1.595 1.595 0 0 0 1.9.268l3.231-1.79l-.06-.06a17.2 17.2 0 0 0 4.86 2.016h-.082l1.02 3.55A1.595 1.595 0 0 0 22.36 45.5h3.28c.711 0 1.337-.471 1.533-1.155l1.02-3.55h-.079a17.2 17.2 0 0 0 4.86-2.017l-.063.063l3.231 1.789a1.595 1.595 0 0 0 1.9-.267l2.32-2.32a1.595 1.595 0 0 0 .268-1.9l-1.79-3.233l-.06.06a17.2 17.2 0 0 0 2.015-4.86v.082l3.55-1.02A1.595 1.595 0 0 0 45.5 25.64v-3.28c0-.711-.471-1.337-1.155-1.533M24 19.925v4.553");
}

.t238zrbfy {
  cx: 24px;
  cy: 24px;
  r: 13px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
