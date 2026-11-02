<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwvgdlbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-right-bulk-sharp" /></template>
<style>
.iwvgdlbie {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 15V9a1 1 0 0 1 1-1h7V4a1.002 1.002 0 0 1 1.707-.707l8 8a1 1 0 0 1 0 1.414l-8 8A1 1 0 0 1 11 20v-4H4a1 1 0 0 1-1-1");
}

</style>
