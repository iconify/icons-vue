<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cxzie-rdv"/><path class="h9i9z_b2s"/><path class="lub9ydbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lefun-health" /></template>
<style>
.cxzie-rdv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.846 25.673c-4.461-4.461-4.461-11.694 0-16.154s11.693-4.461 16.154 0M7.846 25.673L24 41.827l16.154-16.154");
}

.h9i9z_b2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.154 25.673L24 41.827L7.846 25.673m5.384-5.385a3.808 3.808 0 1 1 5.385-5.385M24 9.518l-10.77 10.77m26.924 5.385c4.461-4.461 4.461-11.694 0-16.154S28.461 5.057 24 9.519");
}

.lub9ydbpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.23 31.058l16.155-16.155a3.808 3.808 0 1 1 5.384 5.385L24 31.058");
}

</style>
