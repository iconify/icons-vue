<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bbcxwvjzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-pdf-32-filled" /></template>
<style>
.bbcxwvjzb {
  fill: currentColor;
  d: path("M4 20c1.913 0 3.5 1.592 3.5 3.5A3.5 3.5 0 0 1 4 27H3v2a1 1 0 1 1-2 0v-8a1 1 0 0 1 1-1zm7.5 0a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H10a1 1 0 0 1-1-1v-8a1 1 0 0 1 1-1zm11 0a1 1 0 1 1 0 2H19v2h3a1 1 0 1 1 0 2h-3v3a1 1 0 1 1-2 0v-8a1 1 0 0 1 1-1zM16 9.75A3.25 3.25 0 0 0 19.25 13H27v13.75A3.25 3.25 0 0 1 23.75 30h-3.46a2.5 2.5 0 0 0 .21-1v-1.5H22a2.5 2.5 0 0 0 2.5-2.5a2.5 2.5 0 0 0-.786-1.816A2.497 2.497 0 0 0 22.5 18.5H18a2.5 2.5 0 0 0-2.406 1.827A5.5 5.5 0 0 0 11.5 18.5H10a2.5 2.5 0 0 0-2.332 1.604A5 5 0 0 0 5 18.602V5.25A3.25 3.25 0 0 1 8.25 2H16zM11 28h.5a2 2 0 0 0 2-2v-2a2 2 0 0 0-2-2H11zm-8-3h1a1.5 1.5 0 0 0 1-.385a1.494 1.494 0 0 0 .008-2.223A1.5 1.5 0 0 0 4 22H3zM18 2.137a3.25 3.25 0 0 1 1.366.815l6.682 6.682c.384.384.662.855.815 1.366H19.25c-.69 0-1.25-.56-1.25-1.25z");
}

</style>
