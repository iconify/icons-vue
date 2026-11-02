<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc2-nsv5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-fill-sharp" /></template>
<style>
.gc2-nsv5c {
  fill: currentColor;
  d: path("M4 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v11h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h1Zm16 13H4v2h16Z");
}

</style>
