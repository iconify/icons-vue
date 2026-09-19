<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dc-u1xbrz"/><path class="dp2pk4big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dm-unipd" /></template>
<style>
.dc-u1xbrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h15.725v15.725H5.5M42.5 5.5v15.725H26.775V5.5m-5.55 37V26.775H5.5V42.5m37-15.725H26.775V42.5H42.5");
}

.dp2pk4big {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5a7.863 7.863 0 0 1 0 15.725h0zm37 0a7.863 7.863 0 0 1-15.725 0zm-37 37a7.863 7.863 0 0 1 15.725 0zm37 0a7.863 7.863 0 0 1 0-15.725z");
}

</style>
