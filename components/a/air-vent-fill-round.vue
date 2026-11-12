<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="env5hbroj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:air-vent-fill-round" /></template>
<style>
.env5hbroj {
  fill: currentColor;
  d: path("M7 2h2a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5m0 15V7a1 1 0 0 0-2 0v10a1 1 0 0 0 2 0m4 0V7a1 1 0 0 0-2 0v10a1 1 0 0 0 2 0M21 6a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
