<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pzwz2ib-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-16-filled" /></template>
<style>
.pzwz2ib-w {
  fill: currentColor;
  d: path("M2.75 2A1.75 1.75 0 0 0 1 3.75v8.5c0 .966.784 1.75 1.75 1.75H6c.788 0 1.499-.331 2-.863A2.74 2.74 0 0 0 10 14h3.25A1.75 1.75 0 0 0 15 12.25v-8.5A1.75 1.75 0 0 0 13.25 2H10c-.788 0-1.499.331-2 .863A2.74 2.74 0 0 0 6 2zm4.5 2.75v6.5c0 .69-.56 1.25-1.25 1.25H2.75a.25.25 0 0 1-.25-.25v-8.5a.25.25 0 0 1 .25-.25H6c.69 0 1.25.56 1.25 1.25m1.5 6.5v-6.5c0-.69.56-1.25 1.25-1.25h3.25a.25.25 0 0 1 .25.25v8.5a.25.25 0 0 1-.25.25H10c-.69 0-1.25-.56-1.25-1.25");
}

</style>
