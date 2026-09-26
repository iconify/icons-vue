<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr7e7ob8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-24-filled" /></template>
<style>
.qr7e7ob8a {
  fill: currentColor;
  d: path("M14.042 1.713a1 1 0 0 1 1.916.574l-6 20a1 1 0 0 1-1.916-.574zm-7.749 4.58a1 1 0 0 1 1.414 1.414L3.414 12l4.293 4.293a1 1 0 0 1-1.414 1.414l-5-5a1 1 0 0 1 0-1.414zm10 0a1 1 0 0 1 1.414 0l5 5a1 1 0 0 1 0 1.414l-5 5a1 1 0 0 1-1.414-1.414L20.586 12l-4.293-4.293a1 1 0 0 1 0-1.414");
}

</style>
