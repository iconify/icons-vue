<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6345wbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-down-fill-sharp" /></template>
<style>
.t6345wbvn {
  fill: currentColor;
  d: path("M15 3a1 1 0 0 1 1 1v7h4a1.002 1.002 0 0 1 .707 1.707l-8 8a1 1 0 0 1-1.414 0l-8-8A1 1 0 0 1 4 11h4V4a1 1 0 0 1 1-1Z");
}

</style>
