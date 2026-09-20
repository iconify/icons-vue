<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yl9kfnbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sort-16-regular" /></template>
<style>
.yl9kfnbns {
  fill: currentColor;
  d: path("M4.854 2.146a.5.5 0 0 0-.708 0l-3 3a.5.5 0 1 0 .708.708L4 3.707V13.5a.5.5 0 0 0 1 0V3.707l2.146 2.147a.5.5 0 1 0 .708-.708zm6.299 11.714a.5.5 0 0 0 .694 0l3-2.9a.5.5 0 1 0-.694-.72L12 12.321v-9.82a.5.5 0 0 0-1 0v9.82l-2.152-2.08a.5.5 0 1 0-.696.718z");
}

</style>
