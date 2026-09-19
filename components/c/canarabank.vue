<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p64-5pb5u"/><path class="nqj_edxnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:canarabank" /></template>
<style>
.nqj_edxnd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.211 24.763L4.5 27.055l15.366 12.221l13.12-16.983l-8.939 1.494");
}

.p64-5pb5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.935 31.709l-5.675-.7L30.2 8.724l13.3 25.52l-15.178-1.871");
}

</style>
