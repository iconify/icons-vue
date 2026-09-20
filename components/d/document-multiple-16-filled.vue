<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pfo3exb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-multiple-16-filled" /></template>
<style>
.pfo3exb4f {
  fill: currentColor;
  d: path("M14 6a1 1 0 0 0-1-1v6a3 3 0 0 1-3 3H5a1 1 0 0 0 1 1h4.21A3.79 3.79 0 0 0 14 11.21zM7 1v3.5A1.5 1.5 0 0 0 8.5 6h3.502v5.5a1.5 1.5 0 0 1-1.5 1.5H4.5A1.5 1.5 0 0 1 3 11.5v-9A1.5 1.5 0 0 1 4.5 1zm1 .25V4.5a.5.5 0 0 0 .5.5h3.25z");
}

</style>
