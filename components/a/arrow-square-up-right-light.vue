<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="d68_uj22w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-square-up-right-light" /></template>
<style>
.d68_uj22w {
  fill: currentColor;
  d: path("M208 34H48a14 14 0 0 0-14 14v160a14 14 0 0 0 14 14h160a14 14 0 0 0 14-14V48a14 14 0 0 0-14-14m2 174a2 2 0 0 1-2 2H48a2 2 0 0 1-2-2V48a2 2 0 0 1 2-2h160a2 2 0 0 1 2 2ZM166 96v48a6 6 0 0 1-12 0v-33.52l-53.76 53.76a6 6 0 0 1-8.48-8.48L145.52 102H112a6 6 0 0 1 0-12h48a6 6 0 0 1 6 6");
}

</style>
