<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nh7tcwwbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-off-20-filled" /></template>
<style>
.nh7tcwwbp {
  fill: currentColor;
  d: path("m15.292 16l1.854 1.854a.5.5 0 0 0 .708-.708l-15-15a.5.5 0 1 0-.708.708l1.855 1.854A8 8 0 0 0 15.293 16M18 10c0 1.667-.51 3.215-1.382 4.496L5.504 3.382A8 8 0 0 1 18 10");
}

</style>
