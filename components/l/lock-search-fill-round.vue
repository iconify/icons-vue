<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvpvih20t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-search-fill-round" /></template>
<style>
.uvpvih20t {
  fill: currentColor;
  d: path("M7 8.099V7a5 5 0 0 1 10 0v1.099A5.01 5.01 0 0 1 21 13v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5v-4a5.01 5.01 0 0 1 4-4.901M15 7a3 3 0 1 0-6 0v1h6Zm-2.707 9.708l2 1.999a.999.999 0 1 0 1.414-1.414l-1.999-2a3 3 0 1 0-1.415 1.415");
}

</style>
