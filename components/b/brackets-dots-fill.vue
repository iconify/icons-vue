<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-0paqbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brackets-dots-fill" /></template>
<style>
.e-0paqbpt {
  fill: currentColor;
  d: path("M6 4H4v16h2a1 1 0 0 1 0 2H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h2a1 1 0 0 1 0 2m12-2h2a2 2 0 0 1 2 2v16a2 2 0 0 1-2 2h-2a1 1 0 0 1 0-2h2V4h-2a1 1 0 0 1 0-2M9 5h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-6 6h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-6 6h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2");
}

</style>
