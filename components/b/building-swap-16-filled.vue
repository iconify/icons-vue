<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gc-3-qhdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:building-swap-16-filled" /></template>
<style>
.gc-3-qhdx {
  fill: currentColor;
  d: path("M3 3.5A1.5 1.5 0 0 1 4.5 2h4A1.5 1.5 0 0 1 10 3.5V7h.5A1.5 1.5 0 0 1 12 8.5V11h-1.085a1.5 1.5 0 0 0-2.476-1.56l-2 2a1.5 1.5 0 0 0 0 2.12l.44.44H3.5a.5.5 0 0 1-.5-.5zM5.5 5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m0 2.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m0 2.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m2-5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m0 2.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m2.354 3.354a.5.5 0 0 0-.708-.708l-2 2a.5.5 0 0 0 0 .708l2 2a.5.5 0 0 0 .708-.708L8.707 13h5.586l-1.147 1.146a.5.5 0 0 0 .708.708l2-2a.5.5 0 0 0 0-.708l-2-2a.5.5 0 0 0-.708.708L14.293 12H8.707z");
}

</style>
