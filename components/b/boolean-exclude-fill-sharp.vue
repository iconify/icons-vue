<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7na2kbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-exclude-fill-sharp" /></template>
<style>
.e7na2kbii {
  fill: currentColor;
  d: path("M14 9H9v5l-2 2H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v4Zm-6 8l2-2h5v-5l2-2h4a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1Z");
}

</style>
