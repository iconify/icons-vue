<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="efqo1672e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:liteboxer" /></template>
<style>
.efqo1672e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.667 5.5v24.667H33.25a3.083 3.083 0 0 1 0 6.167H5.5V5.5m12.333 0V24H33.25a9.25 9.25 0 0 1 0 18.5H5.5M33.25 24a9.25 9.25 0 0 0 0-18.5H24m0 6.166h9.25a3.083 3.083 0 0 1 0 6.167H24");
}

</style>
