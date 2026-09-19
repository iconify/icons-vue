<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="pe08h2zup"/><path class="vr29wtorq"/></g><path class="bag4m3bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-tuta-19" /></template>
<style>
.bag4m3bbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.27h28.377L42.5 13.893H14.123zm37-28.428H14.123L5.5 5.73h28.377zM5.5 42.27V5.73");
}

.pe08h2zup {
  d: path("M30.978 20.8c2.65 0 4.143 2.149 3.332 4.8s-3.616 4.8-6.267 4.8s-4.143-2.149-3.333-4.8s3.617-4.8 6.268-4.8");
}

.vr29wtorq {
  d: path("M22.852 33.422c.385 1.067 1.412 1.778 3.368 1.778h.355c2.667 0 5.453-2.133 6.268-4.8l1.467-4.8m-17.437-2.82l4.205-1.98m0 0l-4.402 14.4");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
