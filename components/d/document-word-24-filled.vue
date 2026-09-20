<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwib7fb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-word-24-filled" /></template>
<style>
.mwib7fb6b {
  fill: currentColor;
  d: path("M10 11a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2zm2-3a2 2 0 0 0 2 2h6v10a2 2 0 0 1-2 2h-5.769A2.98 2.98 0 0 0 13 20v-7a3 3 0 0 0-3-3H4V4a2 2 0 0 1 2-2h6zm-3.192 5.501L8.06 17.46l-.797-3.959H5.7l-.76 3.959l-.767-3.959H2.9L4.142 19.5h1.56l.798-3.6l.763 3.6l1.545-.001L10.1 13.5zM19.5 8.5H14a.5.5 0 0 1-.5-.5V2.5z");
}

</style>
