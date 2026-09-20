<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3a6wq54w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:edit-24-filled" /></template>
<style>
.d3a6wq54w {
  fill: currentColor;
  d: path("M15.891 3.048a3.578 3.578 0 1 1 5.061 5.06l-.892.893L15 3.94zM13.94 5.001L3.94 15a3.1 3.1 0 0 0-.825 1.476L2.02 21.078a.75.75 0 0 0 .904.903l4.601-1.096a3.1 3.1 0 0 0 1.477-.825L19 10.061z");
}

</style>
