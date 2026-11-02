<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbwubhb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-minus-fill" /></template>
<style>
.zbwubhb-d {
  fill: currentColor;
  d: path("M7 3a1 1 0 0 1 2 0v1h6V3a1 1 0 0 1 2 0v1h1a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h1ZM5 19a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-9H5Zm4-5h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
