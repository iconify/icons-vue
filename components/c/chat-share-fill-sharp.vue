<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq_hd8b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-share-fill-sharp" /></template>
<style>
.iq_hd8b6g {
  fill: currentColor;
  d: path("m7.414 18l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1Zm9.293-8.707l-3-3a.999.999 0 1 0-1.414 1.414L13.586 9H8a1 1 0 0 0-1 1v3a1 1 0 0 0 2 0v-2h4.586l-1.293 1.293a.999.999 0 1 0 1.414 1.414l3-3a1 1 0 0 0 0-1.414");
}

</style>
