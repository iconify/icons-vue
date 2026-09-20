<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="a7n5ijbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-right-28-regular" /></template>
<style>
.a7n5ijbsv {
  fill: currentColor;
  d: path("M14 24.5C8.201 24.5 3.5 19.799 3.5 14S8.201 3.5 14 3.5S24.5 8.201 24.5 14S19.799 24.5 14 24.5M2 14c0 6.627 5.373 12 12 12s12-5.373 12-12S20.627 2 14 2S2 7.373 2 14m9.22 4.97a.75.75 0 1 0 1.06 1.06l5.5-5.5a.75.75 0 0 0 0-1.06l-5.5-5.5a.75.75 0 1 0-1.06 1.06L16.19 14z");
}

</style>
