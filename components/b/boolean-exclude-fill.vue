<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lojtlhb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-exclude-fill" /></template>
<style>
.lojtlhb9x {
  fill: currentColor;
  d: path("M9 9v5l-2 2H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v3l-2 2Zm-1 8l2-2h5v-5l2-2h3a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H10a2 2 0 0 1-2-2Z");
}

</style>
