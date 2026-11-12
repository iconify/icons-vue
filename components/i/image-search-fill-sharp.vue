<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpv08ibsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-search-fill-sharp" /></template>
<style>
.dpv08ibsj {
  fill: currentColor;
  d: path("m17.414 22l-9.707-9.707a1 1 0 0 0-1.414 0L2 16.586V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1Zm-2.121-11.292l2 1.999a.999.999 0 1 0 1.414-1.414l-1.999-2a3 3 0 1 0-1.415 1.415M4 17.414l3-3L14.586 22H3a1 1 0 0 1-1-1v-1.586Z");
}

</style>
