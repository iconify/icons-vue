<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7ckzbbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-fresh-produce" /></template>
<style>
.h7ckzbbgo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.85 6.853q.873-.27 1.838-.35q3.506-.293 4.983 2.662q.01.019.018.04q1.406 3.279-.727 6.982Q16.623 20.25 12 20.25t-6.962-4.063q-2.133-3.703-.727-6.982q.008-.021.018-.04Q5.806 6.21 9.312 6.503q1.057.088 2.003.404q.484-3.832 4.538-4.642q.072-.015.146-.015t.147.014q.072.015.14.043t.13.069t.114.093t.093.114t.07.129q.028.068.042.141t.015.146t-.014.147q-.015.072-.043.14t-.069.13t-.093.114t-.114.093q-.061.041-.129.07q-.068.028-.141.042q-2.813.563-3.297 3.118");
}

</style>
