<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="o-afpts5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bluetooth-28-regular" /></template>
<style>
.o-afpts5l {
  fill: currentColor;
  d: path("M13.463 2.057a.75.75 0 0 1 .817.163l6 6a.75.75 0 0 1-.036 1.094L14.889 14l5.355 4.686a.75.75 0 0 1 .036 1.094l-6 6a.75.75 0 0 1-1.28-.53v-9.597l-4.756 4.161a.75.75 0 1 1-.988-1.128L12.611 14L7.256 9.314a.75.75 0 1 1 .988-1.128L13 12.347V2.75a.75.75 0 0 1 .463-.693M14.5 15.653v7.786l4.153-4.152zm0-3.306l4.153-3.634L14.5 4.561z");
}

</style>
