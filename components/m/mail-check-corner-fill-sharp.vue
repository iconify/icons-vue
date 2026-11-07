<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtp9qdbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-check-corner-fill-sharp" /></template>
<style>
.mtp9qdbjh {
  fill: currentColor;
  d: path("m4.414 5l-1-1h17.172l-6 6H9.414ZM2 19V5.414l6.293 6.293A1 1 0 0 0 9 12h3v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1M20 7.414l2-2V11a1 1 0 0 1-1 1h-5.586Zm-4.293 9.879L17 18.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a1 1 0 0 1 1.414-1.414");
}

</style>
