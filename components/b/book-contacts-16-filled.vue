<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zbxaau05j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-contacts-16-filled" /></template>
<style>
.zbxaau05j {
  fill: currentColor;
  d: path("M11 1a2 2 0 0 1 2 2v9.497a.5.5 0 0 1-.5.5H4V13a1 1 0 0 0 1 1h7.5a.5.5 0 0 1 0 1H5a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2zM6.7 7a1.2 1.2 0 0 0-1.2 1.2c0 .829.781 1.8 2.5 1.8s2.5-.971 2.5-1.8A1.2 1.2 0 0 0 9.3 7zM8 3.5A1.25 1.25 0 1 0 8 6a1.25 1.25 0 0 0 0-2.5");
}

</style>
