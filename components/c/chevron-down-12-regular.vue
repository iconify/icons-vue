<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jyzd8zb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-down-12-regular" /></template>
<style>
.jyzd8zb8b {
  fill: currentColor;
  d: path("M2.146 4.646a.5.5 0 0 1 .708 0L6 7.793l3.146-3.147a.5.5 0 1 1 .708.708l-3.5 3.5a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 0 1 0-.708");
}

</style>
