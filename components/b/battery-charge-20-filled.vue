<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zsa3ts3wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-charge-20-filled" /></template>
<style>
.zsa3ts3wb {
  fill: currentColor;
  d: path("M6.233 6.176c-.42.832.184 1.82 1.12 1.82H8v1.67c0 1.397 1.884 1.853 2.518.6l2.248-4.446c.136-.27.163-.556.107-.82H16a3 3 0 0 1 3 3a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1l-.004.154A3 3 0 0 1 16 15H3a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3h3.828zm3.14-3.994c.157-.31.625-.2.625.148v2.671h1.647c.19 0 .313.2.227.37L9.624 9.816c-.157.31-.624.198-.624-.149v-2.67H7.353c-.19 0-.313-.2-.228-.37z");
}

</style>
