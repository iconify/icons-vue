<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb-o_ebkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:images-fill" /></template>
<style>
.rb-o_ebkg {
  fill: currentColor;
  d: path("M7 2h12a3 3 0 0 1 3 3v12a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1H7a1 1 0 0 1 0-2M5 6h10a3 3 0 0 1 3 3v7.586l-2.293-2.293a2.41 2.41 0 0 0-3.414 0a.414.414 0 0 1-.586 0l-2-2a2.414 2.414 0 0 0-3.414 0L2 16.586V9a3 3 0 0 1 3-3m12.707 13.121q.121.122.277.196A3 3 0 0 1 15 22H5a3 3 0 0 1-2.984-2.683a1 1 0 0 0 .277-.196l5.414-5.414a.414.414 0 0 1 .586 0l2 2a2.41 2.41 0 0 0 3.414 0a.414.414 0 0 1 .586 0Z");
}

</style>
