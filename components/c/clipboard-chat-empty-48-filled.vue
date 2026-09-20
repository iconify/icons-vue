<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t5ofsdbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-chat-empty-48-filled" /></template>
<style>
.t5ofsdbrn {
  fill: currentColor;
  d: path("M27.75 4a4.25 4.25 0 0 1 4.064 3h3.936A4.25 4.25 0 0 1 40 11.25v7.757A15.05 15.05 0 0 0 31 16c-8.284 0-15 6.716-15 15v.034l.008.46v.035a14.9 14.9 0 0 0 1.442 5.906l-1.313 4.381A3.25 3.25 0 0 0 16.252 44H12.25A4.25 4.25 0 0 1 8 39.75v-28.5A4.25 4.25 0 0 1 12.25 7h3.936a4.25 4.25 0 0 1 4.064-3zm-7.5 2.5a1.75 1.75 0 1 0 0 3.5h7.5a1.75 1.75 0 1 0 0-3.5zM44 31c0 7.18-5.82 13-13 13c-2.261 0-4.39-.58-6.243-1.598l-5.148 1.545a1.25 1.25 0 0 1-1.556-1.556l1.543-5.149a12.9 12.9 0 0 1-1.588-5.782L18 31c0-7.18 5.82-13 13-13s13 5.852 13 13");
}

</style>
