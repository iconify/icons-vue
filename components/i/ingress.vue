<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wfn6j4b4a"/><path class="mhy4xlbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ingress" /></template>
<style>
.mhy4xlbim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37.269L35.668 17.06H12.332zM12.332 17.06L24 23.796m11.668-6.736L24 23.796m0 13.473V23.796");
}

.wfn6j4b4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.978 14.75v18.5L24 42.5l16.021-9.25v-18.5L24 5.5zM24 5.5v8.022m-8.978 15.889L7.978 33.25m24.999-3.839l7.044 3.839");
}

</style>
