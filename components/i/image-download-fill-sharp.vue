<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iikpt2bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-download-fill-sharp" /></template>
<style>
.iikpt2bul {
  fill: currentColor;
  d: path("m17.414 22l-9.707-9.707a1 1 0 0 0-1.414 0L2 16.586V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1Zm-3.121-9.293a1 1 0 0 0 1.414 0l3-3a.999.999 0 1 0-1.414-1.414L16 9.586V6a1 1 0 0 0-2 0v3.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414ZM4 17.414l3-3L14.586 22H3a1 1 0 0 1-1-1v-1.586Z");
}

</style>
