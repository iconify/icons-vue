<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imsslhbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-display-outline-sharp" /></template>
<style>
.imsslhbyw {
  fill: currentColor;
  d: path("M4 12v5.125V4zm2-1h12V9H6zm0-3h12V6H6zM2 22V2h20v10h-2V4H4v13.125L5.15 16H9v2H6zm4-8h3v-2H6zm5 8v-8h11v8zm2-2h7v-4h-7z");
}

</style>
