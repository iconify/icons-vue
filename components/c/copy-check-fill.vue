<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw9qgqfut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-check-fill" /></template>
<style>
.aw9qgqfut {
  fill: currentColor;
  d: path("M9 2h10a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m2.707 7.293a.999.999 0 1 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l4-4a.999.999 0 1 0-1.414-1.414L13 10.586ZM4 9v10a1 1 0 0 0 1 1h10a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V9a1 1 0 0 1 2 0");
}

</style>
