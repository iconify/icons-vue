<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdwc93bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-full-fill-sharp" /></template>
<style>
.hdwc93bys {
  fill: currentColor;
  d: path("M2 7a1 1 0 0 1 1-1h15a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm5 3a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm3 4v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m3-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm3 4v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m6-4v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
