<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm_nktmaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-close-fill-sharp" /></template>
<style>
.mm_nktmaw {
  fill: currentColor;
  d: path("m7.414 18l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1ZM12 8.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414L10.586 10l-1.293 1.293a.999.999 0 1 0 1.414 1.414L12 11.414l1.293 1.293a.999.999 0 1 0 1.414-1.414L13.414 10l1.293-1.293a.999.999 0 1 0-1.414-1.414Z");
}

</style>
