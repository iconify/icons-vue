<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n6_dmbdgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-double-left-16-filled" /></template>
<style>
.n6_dmbdgl {
  fill: currentColor;
  d: path("M6.97 3.22a.75.75 0 1 1 1.06 1.06L4.31 8l3.72 3.72a.75.75 0 1 1-1.06 1.06L2.72 8.53a.75.75 0 0 1 0-1.06zm4.5 0a.75.75 0 1 1 1.06 1.06L8.81 8l3.72 3.72a.75.75 0 1 1-1.06 1.06L7.22 8.53a.75.75 0 0 1 0-1.06z");
}

</style>
