<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s3olnu7fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:form-new-32-light" /></template>
<style>
.s3olnu7fm {
  fill: currentColor;
  d: path("M23 15.5a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15M24.5 3A4.5 4.5 0 0 1 29 7.5v8.793a9 9 0 0 0-1-.777V7.5A3.5 3.5 0 0 0 24.5 4h-17A3.5 3.5 0 0 0 4 7.5v17A3.5 3.5 0 0 0 7.5 28h8.017q.354.528.776 1H7.5A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zm-1.25 14.5a.75.75 0 0 0-.75.75V22h-3.75a.75.75 0 0 0 0 1.5h3.75v3.75a.75.75 0 0 0 1.5 0V23.5h3.75a.75.75 0 0 0 0-1.5H24v-3.75a.75.75 0 0 0-.75-.75M10 19.5a3 3 0 1 1 0 6a3 3 0 0 1 0-6m0 1a2 2 0 1 0 0 4a2 2 0 0 0 0-4m0-9a3 3 0 1 1 0 6a3 3 0 0 1 0-6m0 1a2 2 0 1 0 0 4a2 2 0 0 0 0-4M23 14a8.96 8.96 0 0 0-4.122 1H15.5a.5.5 0 0 1 0-1zm1.5-6a.5.5 0 0 1 0 1h-17a.5.5 0 0 1 0-1z");
}

</style>
