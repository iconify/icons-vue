<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwhiwucps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-split-bottom-focus-top-24-filled" /></template>
<style>
.lwhiwucps {
  fill: currentColor;
  d: path("M3 6.25A3.25 3.25 0 0 1 6.25 3h11.5A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75zM19.5 12h-6.75v7.5h5a1.75 1.75 0 0 0 1.75-1.75zm-8.25 0H4.5v5.75c0 .966.784 1.75 1.75 1.75h5z");
}

</style>
