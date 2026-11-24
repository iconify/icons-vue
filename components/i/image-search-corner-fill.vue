<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi57tos3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-search-corner-fill" /></template>
<style>
.vi57tos3s {
  fill: currentColor;
  d: path("m12.061 12.647l-1.354-1.354a2.415 2.415 0 0 0-3.414 0L2 16.586V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v6a1 1 0 0 1-1 1h-8c-.411 0-.789.264-.939.647M15 10a2 2 0 1 0 .001-3.999A2 2 0 0 0 15 10m-5.707 2.707l2.414 2.414a1 1 0 0 0 .293.203V21a1 1 0 0 1-1 1H5a3 3 0 0 1-2.984-2.683a1 1 0 0 0 .277-.196l6.414-6.414a.414.414 0 0 1 .586 0m12.028 7.2l1.386 1.386a.999.999 0 1 1-1.414 1.414l-1.386-1.386a3.83 3.83 0 1 1 1.414-1.414m-2.028-.614a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586");
}

</style>
