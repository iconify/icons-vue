<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="taaej7ixy"/><circle class="i-j89sbtq"/><path class="px2581bmy"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:2600emu" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.i-j89sbtq {
  cx: 20.122px;
  cy: 25.383px;
  r: 2.765px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.px2581bmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.58 20.876c-.41-.614-1.127-1.024-2.253-1.024h-.205c-1.536 0-2.765 1.229-2.765 2.663v2.868");
}

.taaej7ixy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 22.588c0-1.639 1.536-2.97 3.278-2.663c1.126.205 2.048 1.23 2.15 2.356c0 .82-.204 1.741-.819 2.253c-1.127.922-4.609 3.585-4.609 3.585h5.429m15.066-6.899l-3.951 6.025m2.067.903zc-1.536 0-2.765-1.229-2.765-2.663V22.72c0-1.537 1.229-2.663 2.663-2.663c1.536 0 2.663 1.229 2.663 2.663v2.765c.204 1.537-1.025 2.663-2.561 2.663m9.689-7.03l-3.95 6.024m2.067.904zc-1.536 0-2.765-1.23-2.765-2.663v-2.766a2.644 2.644 0 0 1 2.662-2.663c1.537 0 2.663 1.23 2.663 2.663v2.766c.205 1.536-1.024 2.663-2.56 2.663");
}

</style>
