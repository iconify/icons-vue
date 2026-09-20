<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m84701b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-fit-in-24-regular" /></template>
<style>
.m84701b7j {
  fill: currentColor;
  d: path("M6.238 7.452a.75.75 0 0 0-.036 1.06L8.524 11H2.75a.75.75 0 0 0 0 1.5h5.774l-2.322 2.488a.75.75 0 1 0 1.096 1.024l3.5-3.75a.75.75 0 0 0 0-1.024l-3.5-3.75a.75.75 0 0 0-1.06-.036m11.524 0a.75.75 0 0 1 .036 1.06L15.476 11h5.774a.75.75 0 0 1 0 1.5h-5.774l2.322 2.488a.75.75 0 1 1-1.096 1.024l-3.5-3.75a.75.75 0 0 1 0-1.024l3.5-3.75a.75.75 0 0 1 1.06-.036");
}

</style>
