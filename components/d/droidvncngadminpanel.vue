<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ju_ervb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:droidvncngadminpanel" /></template>
<style>
.ju_ervb9p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.363 42.353V31.745H24.01a7.744 7.744 0 1 0 0-15.489H5.363V5.647H24.01a18.353 18.353 0 0 1 0 36.707Z");
}

</style>
