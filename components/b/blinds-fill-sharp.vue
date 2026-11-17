<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr8wyxb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:blinds-fill-sharp" /></template>
<style>
.sr8wyxb0n {
  fill: currentColor;
  d: path("M3 2h18a1 1 0 0 1 0 2h-1v2H4V4H3a1 1 0 0 1 0-2m17 6v2H4V8Zm0 4v3a1 1 0 0 1-1 1h-6v.171a3 3 0 1 1-2 0V16H5a1 1 0 0 1-1-1v-3Z");
}

</style>
