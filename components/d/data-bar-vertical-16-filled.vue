<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ty_zuvenm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-vertical-16-filled" /></template>
<style>
.ty_zuvenm {
  fill: currentColor;
  d: path("M3.5 2A1.5 1.5 0 0 0 2 3.5v9a1.5 1.5 0 0 0 3 0v-9A1.5 1.5 0 0 0 3.5 2m4 3A1.5 1.5 0 0 0 6 6.5v6a1.5 1.5 0 0 0 3 0v-6A1.5 1.5 0 0 0 7.5 5m4 3A1.5 1.5 0 0 0 10 9.5v3a1.5 1.5 0 0 0 3 0v-3A1.5 1.5 0 0 0 11.5 8");
}

</style>
