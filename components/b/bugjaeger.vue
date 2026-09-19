<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x1cd2-baa"/><path class="wnaqf7phr"/><circle class="zf9dn8zme"/><path class="prjyvdlay"/><circle class="byxmjacxl"/><path class="evw68xfvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bugjaeger" /></template>
<style>
.byxmjacxl {
  cx: 31.202px;
  cy: 31.862px;
  r: 3.478px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.evw68xfvr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.202 28.383v-1.521m-2.459 2.54l-1.076-1.076m.057 3.536h-1.522m2.541 2.459l-1.076 1.076m3.535-.057v1.522m2.46-2.541l1.076 1.076m-.058-3.535h1.522m-2.54-2.46l1.076-1.076");
}

.prjyvdlay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.798 28.383v-1.521m2.459 2.54l1.076-1.076m-.057 3.536h1.522m-2.541 2.459l1.076 1.076m-3.535-.057v1.522m-2.46-2.541l-1.076 1.076m.058-3.535h-1.522m2.54-2.46l-1.076-1.076m13.472 17.002v-2.296m5.212.951v-2.068");
}

.wnaqf7phr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5a23.45 23.45 0 0 1 8.281 5.576a16.1 16.1 0 0 0-7.57 4.946a13.76 13.76 0 0 1 11.373.321q.271.509.517 1.033a13.66 13.66 0 0 0-8.328 4.633a11.67 11.67 0 0 1 10.02.451a23.4 23.4 0 0 1 .51 4.806c0 .704-.036 1.4-.097 2.088a21.42 21.42 0 0 0-29.411 0a24 24 0 0 1-.098-2.088a23.4 23.4 0 0 1 .51-4.806a11.67 11.67 0 0 1 10.02-.451a13.66 13.66 0 0 0-8.327-4.633q.246-.524.517-1.033a13.76 13.76 0 0 1 11.373-.32a16.1 16.1 0 0 0-7.57-4.947A23.45 23.45 0 0 1 24 2.5m-2.734 42.828v-2.296m-5.212.951v-2.068");
}

.x1cd2-baa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 1 1 2.5 24A21.5 21.5 0 0 1 24 2.5");
}

.zf9dn8zme {
  cx: 16.798px;
  cy: 31.862px;
  r: 3.478px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
