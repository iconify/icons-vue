<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj7jq4s4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-intersect-fill-sharp" /></template>
<style>
.mj7jq4s4n {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2H4v3a1 1 0 0 1-2 0Zm13-1a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0V4h-3a1 1 0 0 1 0-2ZM8 9a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1Zm13-1a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0v-3h-1a1 1 0 0 1 0-2ZM4 11v3h1a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0m18 10a1 1 0 0 1-1 1h-4a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0Zm-12-2v1h3a1 1 0 0 1 0 2H9a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0");
}

</style>
