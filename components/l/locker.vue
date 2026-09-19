<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rc1en_hgr"/><path class="vb_uuxzdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:locker" /></template>
<style>
.rc1en_hgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.24a9 9 0 0 1 9 9h0a9 9 0 1 1-9-9m0 4a3.8 3.8 0 0 1 .91 7.5v2.4a.91.91 0 1 1-1.82 0v-2.4a3.8 3.8 0 0 1 .91-7.5");
}

.vb_uuxzdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.2 4.86L6.69 11.25V27C6.69 35.44 24 43.5 24 43.5S41.31 35.44 41.31 27V11.25L25.8 4.86a4.68 4.68 0 0 0-3.6 0");
}

</style>
