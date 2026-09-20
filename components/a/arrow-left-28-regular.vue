<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="n_r7cmbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-left-28-regular" /></template>
<style>
.n_r7cmbhj {
  fill: currentColor;
  d: path("M12.735 4.21a.75.75 0 0 1 1.04 1.08L5.5 13.25h18.753a.75.75 0 0 1 0 1.5H5.501l8.274 7.959a.75.75 0 0 1-1.04 1.08L3.307 14.72a1 1 0 0 1 0-1.441z");
}

</style>
