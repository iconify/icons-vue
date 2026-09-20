<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pd9ux9bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-double-down-16-filled" /></template>
<style>
.pd9ux9bao {
  fill: currentColor;
  d: path("M11.72 7.97a.75.75 0 1 1 1.06 1.06l-4.25 4.25a.75.75 0 0 1-1.06 0L3.22 9.03a.75.75 0 1 1 1.06-1.06L8 11.69zm0-4.5a.75.75 0 1 1 1.06 1.06L8.53 8.78a.75.75 0 0 1-1.06 0L3.22 4.53a.75.75 0 1 1 1.06-1.06L8 7.19z");
}

</style>
