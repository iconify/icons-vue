<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="iyalgndwr"/><path class="p47fz8bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:black-square-button" /></template>
<style>
.iyalgndwr {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.p47fz8bpy {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M30 28a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h20a2 2 0 0 1 2 2z");
}

</style>
