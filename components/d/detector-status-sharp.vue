<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spwmb-s2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:detector-status-sharp" /></template>
<style>
.spwmb-s2d {
  fill: currentColor;
  d: path("M10.95 21L7.4 17.45l1.425-1.4l2.125 2.125l4.225-4.25L16.6 15.35zM8.1 8l.3 1h7.2l.3-1zm-1.15 3L6 8H3V3h18v5h-3l-1.15 3z");
}

</style>
