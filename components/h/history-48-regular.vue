<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zlg2eob3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:history-48-regular" /></template>
<style>
.zlg2eob3t {
  fill: currentColor;
  d: path("M24 8.5c8.56 0 15.5 6.94 15.5 15.5S32.56 39.5 24 39.5S8.5 32.56 8.5 24q.002-1.302.207-2.542a1.25 1.25 0 0 0-2.466-.407A18 18 0 0 0 6 24c0 9.941 8.059 18 18 18s18-8.059 18-18S33.941 6 24 6a17.94 17.94 0 0 0-12.5 5.048V8.25a1.25 1.25 0 1 0-2.5 0v6.5c0 .69.56 1.25 1.25 1.25h6.5a1.25 1.25 0 1 0 0-2.5h-4.152c2.834-3.076 6.893-5 11.402-5m1 5.75a1.25 1.25 0 1 0-2.5 0v10c0 .69.56 1.25 1.25 1.25h7a1.25 1.25 0 1 0 0-2.5H25z");
}

</style>
