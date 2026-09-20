<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="hk3cddcfq"/><path class="ic23_wbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fortunes" /></template>
<style>
.hk3cddcfq {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 7;
}

.ic23_wbxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6 18.7h4m-4 4h2.6m-2.6-4v8m6.7 0za2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2a2 2 0 0 1 2 2v1.3a2 2 0 0 1-2 2m12.7-5.3v3.3a2 2 0 0 0 2 2a2 2 0 0 0 2-2v-3.3m0 3.3v2m-12.6-3.3a2 2 0 0 1 2-2m-2 0v5.3m24.9-1a1.94 1.94 0 0 1-1.7 1a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2a2 2 0 0 1 2 2v.6h-4m-2.3 2.7v-3.3a2 2 0 0 0-2-2a2 2 0 0 0-2 2v3.3m0-3.3v-2m-10-1.7v6a.94.94 0 0 0 1 1h.3m-2.3-5.3h2.1");
}

</style>
