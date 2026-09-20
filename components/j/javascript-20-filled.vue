<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e8dn0jb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:javascript-20-filled" /></template>
<style>
.e8dn0jb6q {
  fill: currentColor;
  d: path("M14 3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zm-3.5 5a.5.5 0 0 0-.5.5v5a.5.5 0 0 1-.5.5h-1a.5.5 0 0 0 0 1h1a1.5 1.5 0 0 0 1.5-1.5v-5a.5.5 0 0 0-.5-.5M13 8a1.5 1.5 0 0 0-1.5 1.5v1A1.5 1.5 0 0 0 13 12h.5a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5H12a.5.5 0 0 0 0 1h1.5a1.5 1.5 0 0 0 1.5-1.5v-1a1.5 1.5 0 0 0-1.5-1.5H13a.5.5 0 0 1-.5-.5v-1A.5.5 0 0 1 13 9h1.5a.5.5 0 0 0 0-1z");
}

</style>
