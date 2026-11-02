<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_it93bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bus-fill-sharp" /></template>
<style>
.b_it93bun {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1h-1v1a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1h-4v1a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-1H5a1 1 0 0 1-1-1Zm14 1H6v8h12ZM9 5h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2M8 15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm8.01 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
