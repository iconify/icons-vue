<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="u-yr8s1ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:4411" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.u-yr8s1ce {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.715 22.561l-.001-9.061l-4.862 6.086h6.002m-10.845 2.975l-.001-9.061l-4.862 6.086h6.002M17.538 34.5h4.53m-4.53-7.827l2.265-1.234m0 0V34.5m7.441 0h4.53m-4.53-7.827l2.265-1.234m0 0V34.5");
}

</style>
