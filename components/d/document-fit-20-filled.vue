<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="glok1tx3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-fit-20-filled" /></template>
<style>
.glok1tx3h {
  fill: currentColor;
  d: path("M6 2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm1.5 3a.5.5 0 0 0-.5.5v1a.5.5 0 0 1-1 0v-1A1.5 1.5 0 0 1 7.5 4h1a.5.5 0 0 1 0 1zm0 10h1a.5.5 0 0 1 0 1h-1A1.5 1.5 0 0 1 6 14.5v-1a.5.5 0 0 1 1 0v1a.5.5 0 0 0 .5.5M13 5.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 1 0-1h1A1.5 1.5 0 0 1 14 5.5v1a.5.5 0 0 1-1 0zm-.5 9.5a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 1 1 0v1a1.5 1.5 0 0 1-1.5 1.5h-1a.5.5 0 0 1 0-1z");
}

</style>
