<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmtdhzqvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-plus-fill-sharp" /></template>
<style>
.hmtdhzqvo {
  fill: currentColor;
  d: path("m17.414 22l-9.707-9.707a1 1 0 0 0-1.414 0L2 16.586V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1ZM16 8V6a1 1 0 0 0-2 0v2h-2a1 1 0 0 0 0 2h2v2a1 1 0 0 0 2 0v-2h2a1 1 0 0 0 0-2ZM4 17.414l3-3L14.586 22H3a1 1 0 0 1-1-1v-1.586Z");
}

</style>
