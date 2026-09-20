<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u1rqtp0dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-up-left-20-filled" /></template>
<style>
.u1rqtp0dz {
  fill: currentColor;
  d: path("M9.28 3.22a.75.75 0 0 0-1.06 0l-4 4a.75.75 0 0 0 0 1.06l4 4a.75.75 0 0 0 1.06-1.06L6.56 8.5H13a1.5 1.5 0 0 1 1.5 1.5v6.25a.75.75 0 0 0 1.5 0V10a3 3 0 0 0-3-3H6.56l2.72-2.72a.75.75 0 0 0 0-1.06");
}

</style>
