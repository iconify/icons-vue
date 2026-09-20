<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lt0aa7_ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-charge-9-20-filled" /></template>
<style>
.lt0aa7_ps {
  fill: currentColor;
  d: path("M6.233 6.176A1.24 1.24 0 0 0 6.127 7H3a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h11.5a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1h-2.331l.597-1.18c.136-.27.163-.556.107-.82H16a3 3 0 0 1 3 3a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1l-.004.154A3 3 0 0 1 16 15H3a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3h3.828zm3.14-3.994c.157-.31.625-.2.625.148v2.671h1.647c.19 0 .313.2.227.37L9.624 9.816c-.157.31-.624.198-.624-.149v-2.67H7.353c-.19 0-.313-.2-.228-.37z");
}

</style>
