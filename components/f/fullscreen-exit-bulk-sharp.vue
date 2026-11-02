<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa5w3hb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fullscreen-exit-bulk-sharp" /></template>
<style>
.oa5w3hb3t {
  fill: currentColor;
  d: path("M7 7V3a1 1 0 0 1 2 0v5a1 1 0 0 1-1 1H3a1 1 0 0 1 0-2Zm10 0h4a1 1 0 0 1 0 2h-5a1 1 0 0 1-1-1V3a1 1 0 0 1 2 0ZM7 17H3a1 1 0 0 1 0-2h5a1 1 0 0 1 1 1v5a1 1 0 0 1-2 0Zm10 0v4a1 1 0 0 1-2 0v-5a1 1 0 0 1 1-1h5a1 1 0 0 1 0 2Z");
}

</style>
