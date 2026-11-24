<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzy621tzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-minus-fill-round" /></template>
<style>
.gzy621tzx {
  fill: currentColor;
  d: path("M7 8.099V7a5 5 0 0 1 10 0v1.099A5.01 5.01 0 0 1 21 13v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5v-4a5.01 5.01 0 0 1 4-4.901M15 7a3 3 0 1 0-6 0v1h6Zm-6 9h6a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2");
}

</style>
