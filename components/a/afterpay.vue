<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cxysx8ojm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:afterpay" /></template>
<style>
.cxysx8ojm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.343v-2.325c0-2.391 2.588-3.886 4.659-2.69L41.947 16c2.07 1.195 2.07 4.184 0 5.38L28.66 29.052c-2.07 1.195-4.659-.3-4.659-2.69v-4.724c0-2.39-2.588-3.885-4.659-2.69L6.053 26.622c-2.07 1.195-2.07 4.184 0 5.38l13.288 7.671c2.07 1.196 4.659-.299 4.659-2.69v-2.325");
}

</style>
