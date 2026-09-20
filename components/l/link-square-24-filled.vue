<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fak8l7rhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-square-24-filled" /></template>
<style>
.fak8l7rhx {
  fill: currentColor;
  d: path("M6.502 3.003a3.5 3.5 0 0 0-3.5 3.5v6a3.5 3.5 0 0 0 3.5 3.5H7v-2h-.497a1.5 1.5 0 0 1-1.5-1.5v-6a1.5 1.5 0 0 1 1.5-1.5h6a1.5 1.5 0 0 1 1.5 1.5v6a1.5 1.5 0 0 1-1.5 1.5h-1.506v2h1.506a3.5 3.5 0 0 0 3.5-3.5v-6a3.5 3.5 0 0 0-3.5-3.5zM10 11.5a1.5 1.5 0 0 1 1.5-1.5h1.499V8H11.5A3.5 3.5 0 0 0 8 11.5v6a3.5 3.5 0 0 0 3.5 3.5h6a3.5 3.5 0 0 0 3.5-3.5v-6A3.5 3.5 0 0 0 17.5 8h-.495v2h.495a1.5 1.5 0 0 1 1.5 1.5v6a1.5 1.5 0 0 1-1.5 1.5h-6a1.5 1.5 0 0 1-1.5-1.5z");
}

</style>
