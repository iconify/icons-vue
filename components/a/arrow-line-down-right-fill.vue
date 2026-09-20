<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="z_p8v_b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-down-right-fill" /></template>
<style>
.z_p8v_b7c {
  fill: currentColor;
  d: path("M224 40a8 8 0 0 1-8 8H40a8 8 0 0 1 0-16h176a8 8 0 0 1 8 8m-28.94 56.61a8 8 0 0 0-8.72 1.73L144 140.69L85.66 82.34a8 8 0 0 0-11.32 11.32L132.69 152l-42.35 42.34A8 8 0 0 0 96 208h96a8 8 0 0 0 8-8v-96a8 8 0 0 0-4.94-7.39");
}

</style>
