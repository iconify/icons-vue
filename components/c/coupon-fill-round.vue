<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7spb4buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coupon-fill-round" /></template>
<style>
.v7spb4buq {
  fill: currentColor;
  d: path("M18 19H6a4 4 0 0 1-4-4a1 1 0 0 1 1-1a2 2 0 1 0 0-4a1 1 0 0 1-1-1a4 4 0 0 1 4-4h12a4 4 0 0 1 4 4a1 1 0 0 1-1 1a2 2 0 1 0 0 4a1 1 0 0 1 1 1a4 4 0 0 1-4 4M9.01 8H9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m1.697 6.707l4-4a.999.999 0 1 0-1.414-1.414l-4 4a.999.999 0 1 0 1.414 1.414M15 14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
