<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5d702brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brick-wall-fill-round" /></template>
<style>
.a5d702brt {
  fill: currentColor;
  d: path("M11 7H2.099A5.01 5.01 0 0 1 7 3h4Zm10.901 0H13V3h4a5.01 5.01 0 0 1 4.901 4M7 9v2H2V9Zm2 0h6v2H9Zm8 2V9h5v2Zm-6 2v2H2v-2Zm11 0v2h-9v-2ZM7 17v4a5.01 5.01 0 0 1-4.901-4Zm8 4H9v-4h6Zm6.901-4A5.01 5.01 0 0 1 17 21v-4Z");
}

</style>
