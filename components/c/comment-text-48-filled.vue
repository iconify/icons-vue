<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y99lvh_zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-text-48-filled" /></template>
<style>
.y99lvh_zi {
  fill: currentColor;
  d: path("M11.25 6A7.25 7.25 0 0 0 4 13.25v15.5A7.25 7.25 0 0 0 11.25 36H12v5.82c0 1.824 2.057 2.89 3.547 1.838L26.398 36H36.75A7.25 7.25 0 0 0 44 28.75v-15.5A7.25 7.25 0 0 0 36.75 6zm11 17.5a1.25 1.25 0 1 1 0-2.5h13.5a1.25 1.25 0 1 1 0 2.5zm-5.5-2.5a1.25 1.25 0 1 1 0 2.5h-4.5a1.25 1.25 0 1 1 0-2.5zm-4.5 5.5h14.5a1.25 1.25 0 1 1 0 2.5h-14.5a1.25 1.25 0 1 1 0-2.5m20 2.5a1.25 1.25 0 1 1 0-2.5h3.5a1.25 1.25 0 1 1 0 2.5z");
}

</style>
