<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roahvb2is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:component-instance-fill-round" /></template>
<style>
.roahvb2is {
  fill: currentColor;
  d: path("M21.707 10.293a2.414 2.414 0 0 1 0 3.414l-8 8a2.414 2.414 0 0 1-3.414 0l-8-8a2.414 2.414 0 0 1 0-3.414l8-8a2.414 2.414 0 0 1 3.414 0Z");
}

</style>
