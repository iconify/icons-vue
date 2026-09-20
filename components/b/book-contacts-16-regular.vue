<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="erds22bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-contacts-16-regular" /></template>
<style>
.erds22bow {
  fill: currentColor;
  d: path("M11 1a2 2 0 0 1 2 2v9.497a.5.5 0 0 1-.5.5H4V13a1 1 0 0 0 1 1h7.5a.5.5 0 0 1 0 1H5a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2zM5 2a1 1 0 0 0-1 1v8.997h8V3a1 1 0 0 0-1-1zm4.3 5a1.2 1.2 0 0 1 1.2 1.2c0 .829-.781 1.8-2.5 1.8s-2.5-.971-2.5-1.8A1.2 1.2 0 0 1 6.7 7zM8 3.5A1.25 1.25 0 1 1 8 6a1.25 1.25 0 0 1 0-2.5");
}

</style>
