<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7oarub3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gallery-fill" /></template>
<style>
.e7oarub3c {
  fill: currentColor;
  d: path("M5 2h14a3 3 0 0 1 3 3v7.586l-3.293-3.293a2.414 2.414 0 0 0-3.414 0l-1 1a.414.414 0 0 1-.586 0l-3-3a2.414 2.414 0 0 0-3.414 0L2 12.586V5a3 3 0 0 1 3-3m12.293 8.707l4.414 4.414q.121.122.277.196A3 3 0 0 1 19 18H5a3 3 0 0 1-2.984-2.683a1 1 0 0 0 .277-.196l6.414-6.414a.414.414 0 0 1 .586 0l3 3a2.414 2.414 0 0 0 3.414 0l1-1a.414.414 0 0 1 .586 0M10 20a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm11 0a1 1 0 0 1 0 2h-7a1 1 0 0 1 0-2Z");
}

</style>
