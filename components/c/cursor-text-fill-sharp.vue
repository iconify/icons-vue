<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sloqa5btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-text-fill-sharp" /></template>
<style>
.sloqa5btn {
  fill: currentColor;
  d: path("M12 2h4a1 1 0 0 1 0 2h-3v16h3a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2h3V4H8a1 1 0 0 1 0-2Z");
}

</style>
