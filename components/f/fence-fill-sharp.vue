<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soi5eiboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fence-fill-sharp" /></template>
<style>
.soi5eiboe {
  fill: currentColor;
  d: path("M14 17h-4v4a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-4H3a1 1 0 0 1 0-2h1v-4H3a1 1 0 0 1 0-2h1V7c0-.155.036-.308.106-.447l2-4a.998.998 0 0 1 1.788 0l2 4c.07.139.106.292.106.447v2h4V7c0-.155.036-.308.106-.447l2-4a.998.998 0 0 1 1.788 0l2 4c.07.139.106.292.106.447v2h1a1 1 0 0 1 0 2h-1v4h1a1 1 0 0 1 0 2h-1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1Zm-4-6v4h4v-4Z");
}

</style>
