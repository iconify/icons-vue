<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w1uy9vbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-charge-3-20-regular" /></template>
<style>
.w1uy9vbix {
  fill: currentColor;
  d: path("M6.322 6H3a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2h-3.325l.09-.18c.137-.27.164-.556.108-.82H16a3 3 0 0 1 3 3a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1a3 3 0 0 1-3 3H3a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3h3.828zM5.5 7c.304 0 .575.136.759.35q.055.102.129.191A1 1 0 0 1 6.5 8v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1zm3.873-4.818c.157-.31.625-.2.625.148v2.671h1.647c.19 0 .313.2.227.37L9.624 9.816c-.157.31-.624.198-.624-.149v-2.67H7.353c-.19 0-.313-.2-.228-.37z");
}

</style>
