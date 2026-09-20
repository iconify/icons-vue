<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xf_5if01j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-empty-48-filled" /></template>
<style>
.xf_5if01j {
  fill: currentColor;
  d: path("M6 12.25A6.25 6.25 0 0 1 12.25 6h23.5A6.25 6.25 0 0 1 42 12.25V14H6zm0 4.25v19.25A6.25 6.25 0 0 0 12.25 42h23.5A6.25 6.25 0 0 0 42 35.75V16.5z");
}

</style>
