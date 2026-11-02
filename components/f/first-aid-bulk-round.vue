<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc43jw5jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:first-aid-bulk-round" /></template>
<style>
.rc43jw5jh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 8h2a4 4 0 0 1 0 8h-2v2a4 4 0 0 1-8 0v-2H6a4 4 0 0 1 0-8h2V6a4 4 0 0 1 8 0Z");
}

</style>
