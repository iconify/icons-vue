<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss0tn1tgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:delta" /></template>
<style>
.ss0tn1tgd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.179 5.844l6.008 10.68q.703 1.25-.021 2.488t-2.158 1.238H5.992q-1.434 0-2.158-1.238t-.021-2.488l6.008-10.68Q10.538 4.57 12 4.57t2.179 1.274");
}

</style>
