<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iu1hlbblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cointrend" /></template>
<style>
.iu1hlbblj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.91 28.92v.118c0 5.23-4.436 9.472-9.91 9.472h0c-5.474 0-9.91-4.241-9.91-9.472v-9.65c0-5.232 4.436-9.473 9.91-9.473h0c5.474 0 9.91 4.24 9.91 9.472v.117M24.085 44.5v-5.66m-.122-29.68V3.5");
}

</style>
