<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbdejr6hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-left-24-regular" /></template>
<style>
.tbdejr6hh {
  fill: currentColor;
  d: path("M13.246 21.005a.75.75 0 1 0 0-1.5H5.577l15.2-15.2a.765.765 0 0 0-1.082-1.081l-15.199 15.2v-7.67a.75.75 0 0 0-1.5 0v9.5c0 .415.336.75.75.75z");
}

</style>
