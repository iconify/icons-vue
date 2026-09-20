<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hqup8-uiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-search-20-regular" /></template>
<style>
.hqup8-uiy {
  fill: currentColor;
  d: path("M4 4v12a2 2 0 0 0 2 2h9.5a.5.5 0 0 0 0-1H6a1 1 0 0 1-1-1h10a1 1 0 0 0 1-1V4a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2m10-1a1 1 0 0 1 1 1v11H5V4a1 1 0 0 1 1-1zm-2.414 6.879a2.5 2.5 0 1 0-.707.707l1.267 1.268a.5.5 0 0 0 .708-.708zM8 8.5a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0");
}

</style>
