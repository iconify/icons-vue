<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rskpovb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-top-fill-round" /></template>
<style>
.rskpovb1x {
  fill: currentColor;
  d: path("M21 3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm-10 8v6a4 4 0 0 1-8 0v-6a4 4 0 0 1 8 0m10 0v2a4 4 0 0 1-8 0v-2a4 4 0 0 1 8 0");
}

</style>
