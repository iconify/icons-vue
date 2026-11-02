<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taf--bs9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-plus-fill-round" /></template>
<style>
.taf--bs9f {
  fill: currentColor;
  d: path("M11 2h6a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5h-6a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5m6 7h-2V7a1 1 0 0 0-2 0v2h-2a1 1 0 0 0 0 2h2v2a1 1 0 0 0 2 0v-2h2a1 1 0 0 0 0-2M4 9v8a3 3 0 0 0 3 3h8a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V9a1 1 0 0 1 2 0");
}

</style>
