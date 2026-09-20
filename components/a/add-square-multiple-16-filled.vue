<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cjqlwmgdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-square-multiple-16-filled" /></template>
<style>
.cjqlwmgdt {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2zm4.5 2.5h-2a.5.5 0 0 0 0 1h2v2a.5.5 0 0 0 1 0v-2h2a.5.5 0 1 0 0-1h-2v-2a.5.5 0 0 0-1 0zm4 6.5a2.5 2.5 0 0 0 2.5-2.5V3.268A2 2 0 0 1 14 5v5.5a3.5 3.5 0 0 1-3.5 3.5H5a2 2 0 0 1-1.732-1z");
}

</style>
