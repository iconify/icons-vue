<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-qx0rbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coupon-fill-sharp" /></template>
<style>
.k-qx0rbue {
  fill: currentColor;
  d: path("M22 9a1 1 0 0 1-1 1a2 2 0 1 0 0 4a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1a2 2 0 1 0 0-4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1ZM9.01 8H9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m1.697 6.707l4-4a.999.999 0 1 0-1.414-1.414l-4 4a.999.999 0 1 0 1.414 1.414M15 14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
