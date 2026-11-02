<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo523kb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-open-fill-sharp" /></template>
<style>
.fo523kb4z {
  fill: currentColor;
  d: path("M10 6v3h10a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1h4V6a4 4 0 0 1 8 0a1 1 0 0 1-2 0a2 2 0 0 0-3.843-.778A2 2 0 0 0 10 6");
}

</style>
