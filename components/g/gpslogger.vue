<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="kzbvcpbzi"/><path class="a-_t87bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gpslogger" /></template>
<style>
.a-_t87bab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.04 5.51l-.8-3m10.72 40l.8 2.98M42.5 19.05l3-.81m-40 10.72l-3 .81");
}

.kzbvcpbzi {
  cx: 24px;
  cy: 24.01px;
  r: 19.15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
