<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juzg_5j5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-off-fill" /></template>
<style>
.juzg_5j5e {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-4.755-4.755A3 3 0 0 1 16 18H5a3 3 0 0 1-3-3V9a3 3 0 0 1 2.611-2.975L1.293 2.707a.999.999 0 1 1 1.414-1.414M19 14.757L10.243 6H16a3 3 0 0 1 3 3ZM22 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
