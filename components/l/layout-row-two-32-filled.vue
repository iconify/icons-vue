<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xqock-bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-32-filled" /></template>
<style>
.xqock-bmk {
  fill: currentColor;
  d: path("M7.5 3A4.5 4.5 0 0 0 3 7.5V15h26V7.5A4.5 4.5 0 0 0 24.5 3zM29 17H3v7.5A4.5 4.5 0 0 0 7.5 29h17a4.5 4.5 0 0 0 4.5-4.5z");
}

</style>
