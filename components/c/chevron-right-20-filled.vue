<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kna2-fbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-right-20-filled" /></template>
<style>
.kna2-fbfv {
  fill: currentColor;
  d: path("M7.733 4.207a.75.75 0 0 1 1.06.026l5.001 5.25a.75.75 0 0 1 0 1.035l-5 5.25a.75.75 0 1 1-1.087-1.034L12.216 10l-4.51-4.734a.75.75 0 0 1 .027-1.06");
}

</style>
