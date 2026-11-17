<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-nt376ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:doorbell-fill-round" /></template>
<style>
.g-nt376ay {
  fill: currentColor;
  d: path("M10 2h4a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 14 22h-4a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5m4 5h-4a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2m-5 7a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
