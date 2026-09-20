<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgo0h0b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-arrow-up-24-filled" /></template>
<style>
.rgo0h0b2b {
  fill: currentColor;
  d: path("M23 6.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0m-6-1.793V9.5a.5.5 0 0 0 1 0V4.707l1.646 1.647a.5.5 0 0 0 .708-.708l-2.5-2.5a.5.5 0 0 0-.708 0l-2.5 2.5a.5.5 0 0 0 .708.708zM17.5 13a6.48 6.48 0 0 0 4.5-1.81v5.56a3.25 3.25 0 0 1-3.066 3.245L18.75 20H5.25a3.25 3.25 0 0 1-3.245-3.066L2 16.75V8.608l9.652 5.056a.75.75 0 0 0 .696 0l2.417-1.266A6.5 6.5 0 0 0 17.5 13M5.25 4h6.248A6.5 6.5 0 0 0 11 6.5c0 1.993.897 3.776 2.308 4.968L12 12.153l-9.984-5.23a3.25 3.25 0 0 1 3.048-2.918z");
}

</style>
