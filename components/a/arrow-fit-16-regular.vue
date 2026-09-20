<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mg8bfacvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-fit-16-regular" /></template>
<style>
.mg8bfacvw {
  fill: currentColor;
  d: path("M3.854 5.146a.5.5 0 0 1 0 .708L2.707 7H6.5a.5.5 0 0 1 0 1H2.707l1.147 1.146a.5.5 0 1 1-.708.708l-2-2a.5.5 0 0 1 0-.708l2-2a.5.5 0 0 1 .708 0m8.292 0a.5.5 0 0 1 .708 0l2 2a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708-.708L13.293 8H9.5a.5.5 0 0 1 0-1h3.793l-1.147-1.146a.5.5 0 0 1 0-.708");
}

</style>
