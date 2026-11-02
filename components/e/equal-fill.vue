<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhqsqi7qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:equal-fill" /></template>
<style>
.bhqsqi7qs {
  fill: currentColor;
  d: path("M18 8a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
