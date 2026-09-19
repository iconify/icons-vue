<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m7mjpacck"/><path class="c5hrqbc_g"/><path class="fdnvarb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hello-kidney-th" /></template>
<style>
.c5hrqbc_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.642 23.735c3.61.028 4.95.886 4.95 3.457v13.376m7.929-24.55c-3.75-2.702-2.447-8.586 4.311-8.586c5.974 0 11.514 7.89 11.514 13.998c0 5.957-5.128 13.557-9.876 13.557c-3.48 0-6.125-1.996-6.47-5.09c-.297-3.82 2.651-4.801 3.237-8.111c.333-1.882-.058-3.852-2.716-5.767");
}

.fdnvarb1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.358 23.735c-3.61.028-4.95.886-4.95 3.457v13.376");
}

.m7mjpacck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.48 16.019c3.748-2.702 2.446-8.587-4.312-8.587c-5.974 0-11.514 7.89-11.514 13.998c0 5.957 5.128 13.557 9.876 13.557c3.48 0 6.125-1.996 6.47-5.09c.297-3.82-2.651-4.801-3.237-8.111c-.333-1.882.058-3.852 2.716-5.767");
}

</style>
