<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwf6hkbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:detector-status-outline-sharp" /></template>
<style>
.bwf6hkbsn {
  fill: currentColor;
  d: path("M10.95 21L7.4 17.45l1.425-1.4l2.125 2.125l4.225-4.25L16.6 15.35zM5 5v1h14V5zm3.1 3l.3 1h7.2l.3-1zm-1.15 3L6 8H3V3h18v5h-3l-1.15 3zM5 5v1z");
}

</style>
