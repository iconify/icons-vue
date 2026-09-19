<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="buqaa7bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:davia-alt" /></template>
<style>
.buqaa7bzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 29.24h5.86l2.125 2.132l-2.067 2.033H4.5m8.716 0l4.18-4.164l4.245 4.164m13.893 0l3.943-4.164l4.023 4.164m-10.313 0v-4.164m-2.383-.001h-5.86l-2.124 2.132l2.066 2.033h5.918M43.5 14.595H27.933L24 18.528l-3.933-3.933H4.5m0 10.387h15.567L24 21.049l3.933 3.933H43.5");
}

</style>
