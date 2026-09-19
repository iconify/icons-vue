<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iaep_qpkv"/><path class="x-blltjjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kagawabank" /></template>
<style>
.iaep_qpkv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.741 8.763C11.323 8.763 4.5 15.585 4.5 24s6.824 15.237 15.241 15.237a15.24 15.24 0 0 0 14.706-11.316l2.578-9.579s1.56-6.915 6.475-9.578z");
}

.x-blltjjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.44 39.14l5.598-20.798s1.56-6.915 6.475-9.579M11.999 37.128l5.057-18.786s1.56-6.915 6.474-9.579");
}

</style>
