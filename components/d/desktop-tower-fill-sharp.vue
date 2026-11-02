<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id-8k1ham"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:desktop-tower-fill-sharp" /></template>
<style>
.id-8k1ham {
  fill: currentColor;
  d: path("M12 18H3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h9V4a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1Zm5.01-11H17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 10H4v6h8Zm6 6v-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0m-9 3a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
