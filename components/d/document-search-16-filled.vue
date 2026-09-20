<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ln4ubwb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-search-16-filled" /></template>
<style>
.ln4ubwb2t {
  fill: currentColor;
  d: path("M8 1v3.5A1.5 1.5 0 0 0 9.5 6H13v7.5a1.5 1.5 0 0 1-1.5 1.5h-.585a1.5 1.5 0 0 0-.354-1.56l-2-2A4.5 4.5 0 0 0 3 5.256V2.5A1.5 1.5 0 0 1 4.5 1zm1 .25V4.5a.5.5 0 0 0 .5.5h3.25zM6.596 12.303a3.5 3.5 0 1 1 .707-.707l2.55 2.55a.5.5 0 0 1-.707.708zM7 9.5a2.5 2.5 0 1 0-5 0a2.5 2.5 0 0 0 5 0");
}

</style>
