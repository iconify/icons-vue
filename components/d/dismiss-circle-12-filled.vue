<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jb-h5ob7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-circle-12-filled" /></template>
<style>
.jb-h5ob7d {
  fill: currentColor;
  d: path("M6 11A5 5 0 1 0 6 1a5 5 0 0 0 0 10m1.854-6.854a.5.5 0 0 1 0 .708L6.707 6l1.147 1.146a.5.5 0 1 1-.708.708L6 6.707L4.854 7.854a.5.5 0 1 1-.708-.708L5.293 6L4.146 4.854a.5.5 0 1 1 .708-.708L6 5.293l1.146-1.147a.5.5 0 0 1 .708 0");
}

</style>
