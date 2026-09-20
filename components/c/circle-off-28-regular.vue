<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ovceahb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-off-28-regular" /></template>
<style>
.ovceahb2b {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l22.5 22.5a.75.75 0 0 1-1.06 1.06l-2.784-2.784A11.95 11.95 0 0 1 14 26C7.373 26 2 20.627 2 14c0-3.044 1.134-5.822 3.002-7.937L2.22 3.28a.75.75 0 0 1 0-1.06m3.845 4.906A10.46 10.46 0 0 0 3.5 14c0 5.799 4.701 10.5 10.5 10.5c2.63 0 5.03-.97 6.872-2.567zM14 2c6.627 0 12 5.373 12 12c0 2.5-.766 4.821-2.074 6.743l-1.084-1.084A10.45 10.45 0 0 0 24.5 14c0-5.799-4.701-10.5-10.5-10.5c-2.085 0-4.027.61-5.66 1.657L7.256 4.073A11.94 11.94 0 0 1 14 2");
}

</style>
