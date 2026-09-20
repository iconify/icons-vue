<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pqaxqn4zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-vertical-20-filled" /></template>
<style>
.pqaxqn4zt {
  fill: currentColor;
  d: path("M5 3a2 2 0 0 0-2 2v10a2 2 0 1 0 4 0V5a2 2 0 0 0-2-2m5 3a2 2 0 0 0-2 2v7a2 2 0 1 0 4 0V8a2 2 0 0 0-2-2m5 3a2 2 0 0 0-2 2v4a2 2 0 1 0 4 0v-4a2 2 0 0 0-2-2");
}

</style>
