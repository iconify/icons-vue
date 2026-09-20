<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hb3jdcbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-four-16-filled" /></template>
<style>
.hb3jdcbeb {
  fill: currentColor;
  d: path("M8.5 14H11V2H8.5zm-1-12H5v12h2.5zm6.5 9.5a2.5 2.5 0 0 1-2 2.45V2.05a2.5 2.5 0 0 1 2 2.45zM4 2.05A2.5 2.5 0 0 0 2 4.5v7a2.5 2.5 0 0 0 2 2.45z");
}

</style>
