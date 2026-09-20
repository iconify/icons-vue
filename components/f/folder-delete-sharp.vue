<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrd3w3bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-delete-sharp" /></template>
<style>
.nrd3w3bsx {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm11-3h5v-5.5h1V10h-2.5V9h-2v1H12v1.5h1zm1.5-1.5v-4h2v4z");
}

</style>
