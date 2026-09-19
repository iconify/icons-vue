<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xy15grbgw"/><path class="re-rqeb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:daum" /></template>
<style>
.re-rqeb_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.838 42.5H6.662v-37h16.176c10.217 0 18.5 8.283 18.5 18.5s-8.283 18.5-18.5 18.5");
}

.xy15grbgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.85 13.594c5.747 0 10.406 4.659 10.406 10.406s-4.66 10.406-10.407 10.406h-8.093V13.594z");
}

</style>
