<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4ite6bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lens-filter" /></template>
<style>
.v4ite6bnb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m5.123-5.127Q4.75 8.997 4.75 12t2.123 5.127T12 19.25t5.127-2.123Q19.25 15.003 19.25 12t-2.123-5.127Q15.003 4.75 12 4.75T6.873 6.873");
}

</style>
