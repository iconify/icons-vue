<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gwux-1biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-arrow-right-16-filled" /></template>
<style>
.gwux-1biw {
  fill: currentColor;
  d: path("M14 7c0 2.876-3.1 6.01-4.844 7.544a1.736 1.736 0 0 1-2.312 0C5.101 13.01 2 9.876 2 7a6 6 0 1 1 12 0M8.146 4.854L9.293 6H5.5a.5.5 0 0 0 0 1h3.793L8.146 8.146a.5.5 0 1 0 .708.708l2-2a.5.5 0 0 0 0-.708l-2-2a.5.5 0 1 0-.708.708");
}

</style>
