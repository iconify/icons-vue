<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="h8z9qo28r"/><circle class="y2immvofm"/><path class="uu9thnb0c"/><path class="ds6r8yu4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hepsiburada" /></template>
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

.ds6r8yu4s {
  fill: none;
  stroke: currentColor;
  d: path("M8.4 38.835h31.156m-15.558.084v6.545m-8-6.545v5.059m16-5.059v5.059");
}

.h8z9qo28r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 14.526v8.1m0-3.4c0-1.1.9-2 2-2s2 .9 2 2v3.3");
}

.uu9thnb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 17.226v5.4m-5.6-.4c.4.3.8.4 1.6.4h.4c.7 0 1.3-.6 1.3-1.3h0c0-.7-.6-1.3-1.3-1.3H28c-.7 0-1.3-.6-1.3-1.3h0c0-.7.6-1.3 1.3-1.3h.4c.9 0 1.3.1 1.6.4m-11.8 3.8c-.3.6-1 1-1.7 1h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2v.7h-4m6 .574c0 1.1.9 2 2 2h0c1.1 0 2-.9 2-2v-1.3c0-1.1-.9-2-2-2h0c-1.1 0-2 .9-2 2m0-2.1v8m-5.997 2.9v3.3c0 1.1.9 2 2 2s2-.9 2-2v-3.3m0 3.4v2m2.42-3.4c0-1.1.9-2 2-2m-2 0v5.4m7.867-2c0 1.1-.9 2-2 2h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2m-.001 3.3v-5.4m6.001 2c0-1.1-.9-2-2-2h0c-1.1 0-2 .9-2 2v1.3c0 1.1.9 2 2 2h0c1.1 0 2-.9 2-2m-.001 2.1v-8M8.5 30.1c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2v1.3c0 1.1-.9 2-2 2h0c-1.1 0-2-.9-2-2m0 2.1v-8m32.29 6c0 1.1-.9 2-2 2h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2m-.001 3.3v-5.4");
}

.y2immvofm {
  cx: 32.5px;
  cy: 14.826px;
  r: 0.7px;
  fill: currentColor;
}

</style>
