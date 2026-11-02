<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqm_3eb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-check-fill-sharp" /></template>
<style>
.bqm_3eb_c {
  fill: currentColor;
  d: path("m7.414 18l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1Zm2.293-8.707a.999.999 0 1 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l4-4a.999.999 0 1 0-1.414-1.414L11 10.586Z");
}

</style>
