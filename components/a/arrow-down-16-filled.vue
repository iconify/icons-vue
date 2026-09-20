<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p7vhx9bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-16-filled" /></template>
<style>
.p7vhx9bvw {
  fill: currentColor;
  d: path("M8 2a.75.75 0 0 1 .75.75v8.787l2.941-3.287a.75.75 0 1 1 1.118 1L8.559 14a.75.75 0 0 1-1.118 0l-4.25-4.75a.75.75 0 1 1 1.118-1l2.941 3.287V2.75A.75.75 0 0 1 8 2");
}

</style>
