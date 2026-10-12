<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jslvvobah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-pdf-32-regular" /></template>
<style>
.jslvvobah {
  fill: currentColor;
  d: path("M4 20c1.913 0 3.5 1.592 3.5 3.5A3.5 3.5 0 0 1 4 27H3v2a1 1 0 1 1-2 0v-8a1 1 0 0 1 1-1zm-1 5h1a1.5 1.5 0 0 0 1-.385a1.494 1.494 0 0 0 .008-2.223A1.5 1.5 0 0 0 4 22H3zm8.5-5a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H10a1 1 0 0 1-1-1v-8a1 1 0 0 1 1-1zm-.5 8h.5a2 2 0 0 0 2-2v-2a2 2 0 0 0-2-2H11zm11.5-8a1 1 0 1 1 0 2H19v2h3a1 1 0 1 1 0 2h-3v3a1 1 0 1 1-2 0v-8a1 1 0 0 1 1-1zM17.068 2a3.25 3.25 0 0 1 2.298.952l6.682 6.682c.61.61.952 1.436.952 2.298V26.75A3.25 3.25 0 0 1 23.75 30h-3.46a2.5 2.5 0 0 0 .21-1v-1h3.25c.69 0 1.25-.56 1.25-1.25V13h-5.75A3.25 3.25 0 0 1 16 9.75V4H8.25C7.56 4 7 4.56 7 5.25v14.253a5 5 0 0 0-2-.901V5.25A3.25 3.25 0 0 1 8.25 2zM18 9.75c0 .69.56 1.25 1.25 1.25h5.336L18 4.414z");
}

</style>
