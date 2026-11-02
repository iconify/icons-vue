<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hutkjbc0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:devices-fill-sharp" /></template>
<style>
.hutkjbc0h {
  fill: currentColor;
  d: path("M16 5H4v10h7a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0Zm-2 5a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1Z");
}

</style>
