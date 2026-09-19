<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="dxd5muj9i"/><circle class="e3dbg2bxc"/><path class="ese2rkbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alert-for-embrace-watch" /></template>
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

.dxd5muj9i {
  cx: 24px;
  cy: 24px;
  r: 17.451px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e3dbg2bxc {
  cx: 24px;
  cy: 24px;
  r: 13.292px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ese2rkbba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.689 23.998l-1.512-1.49c-1.253-1.235-1.253-3.236 0-4.47s3.284-1.235 4.536 0l1.513 1.49m-4.537 4.47l-1.512 1.49c-.81.799-1.127 1.963-.83 3.054s1.16 1.943 2.268 2.235s2.288-.02 3.098-.818l1.513-1.49m2.268-6.706l2.268 2.235l-2.268 2.235");
}

</style>
