<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="krtolnfnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:beaker-16-filled" /></template>
<style>
.krtolnfnh {
  fill: currentColor;
  d: path("M6 3v3.689a2.5 2.5 0 0 1-.34 1.26L5.045 9h5.908l-.614-1.051a2.5 2.5 0 0 1-.34-1.26V3h.5a.5.5 0 0 0 0-1h-5a.5.5 0 0 0 0 1zm5.537 7H4.463l-1.018 1.744A1.5 1.5 0 0 0 4.741 14h6.518a1.5 1.5 0 0 0 1.296-2.256z");
}

</style>
