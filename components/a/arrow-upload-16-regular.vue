<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pcjfdvbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-upload-16-regular" /></template>
<style>
.pcjfdvbst {
  fill: currentColor;
  d: path("M3.5 2a.5.5 0 0 0 0 1h9a.5.5 0 0 0 0-1zm4.854 2.146a.5.5 0 0 0-.708 0l-3.5 3.5a.5.5 0 1 0 .708.708L7.5 5.707V13.5a.5.5 0 0 0 1 0V5.707l2.646 2.647a.5.5 0 0 0 .708-.708z");
}

</style>
