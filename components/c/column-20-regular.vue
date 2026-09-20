<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o06jmw0lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:column-20-regular" /></template>
<style>
.o06jmw0lz {
  fill: currentColor;
  d: path("M16.5 17a.5.5 0 0 0 0-1H16a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h.5a.5.5 0 0 0 0-1H16a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2zM7 5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2zm5 10V5a1 1 0 0 0-1-1H9a1 1 0 0 0-1 1v10a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1m-8 2a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2h-.5a.5.5 0 0 0 0 1H4a1 1 0 0 1 1 1v10q0 .052-.005.102A1 1 0 0 1 4 16h-.5a.5.5 0 1 0 0 1z");
}

</style>
