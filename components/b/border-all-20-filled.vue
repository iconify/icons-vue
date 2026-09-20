<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xdrr_kd7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-all-20-filled" /></template>
<style>
.xdrr_kd7t {
  fill: currentColor;
  d: path("M6.25 4.5A1.75 1.75 0 0 0 4.5 6.25v3h4.75V4.5zm4.5 0v4.75h4.75v-3a1.75 1.75 0 0 0-1.75-1.75zm4.75 6.25h-4.75v4.75h3a1.75 1.75 0 0 0 1.75-1.75zM9.25 15.5v-4.75H4.5v3c0 .966.784 1.75 1.75 1.75zM3 6.25A3.25 3.25 0 0 1 6.25 3h7.5A3.25 3.25 0 0 1 17 6.25v7.5A3.25 3.25 0 0 1 13.75 17h-7.5A3.25 3.25 0 0 1 3 13.75z");
}

</style>
