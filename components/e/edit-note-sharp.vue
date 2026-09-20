<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jft38cmjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-note-sharp" /></template>
<style>
.jft38cmjx {
  fill: currentColor;
  d: path("M5 14v-1h7v1zm0-4V9h11v1zm0-4V5h11v1zm8.23 13v-2.21l5.96-5.934l2.19 2.204L15.44 19zm5.96-4.985l.925-.956l-.924-.943l-.95.95z");
}

</style>
