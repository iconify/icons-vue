<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hmcgat_gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-microphone-20-filled" /></template>
<style>
.hmcgat_gx {
  fill: currentColor;
  d: path("M18.5 13.5a.5.5 0 0 1 .5.5a4 4 0 0 1-3.5 3.968v.532a.5.5 0 0 1-1 0v-.532A4 4 0 0 1 11 14a.5.5 0 0 1 1 0a3 3 0 1 0 6 0a.5.5 0 0 1 .5-.5M8 3c.788 0 1.499.331 2 .862A2.74 2.74 0 0 1 12 3h4.25c.966 0 1.75.784 1.75 1.75V12c0-1.11-.604-2.077-1.5-2.596V4.75a.25.25 0 0 0-.25-.25H12c-.69 0-1.25.56-1.25 1.25v6.951A1.5 1.5 0 0 0 10 14c0 1.005.297 1.94.808 2.725a2.8 2.8 0 0 1-.808-.587A2.74 2.74 0 0 1 8 17H3.75A1.75 1.75 0 0 1 2 15.25V4.75C2 3.784 2.784 3 3.75 3zm7 7a2 2 0 0 1 2 2v2a2 2 0 1 1-4 0v-2a2 2 0 0 1 2-2M3.75 4.5a.25.25 0 0 0-.25.25v10.5c0 .138.112.25.25.25H8c.69 0 1.25-.56 1.25-1.25v-8.5c0-.69-.56-1.25-1.25-1.25z");
}

</style>
