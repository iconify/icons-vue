<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvswfgbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backspace-fill-round" /></template>
<style>
.mvswfgbpw {
  fill: currentColor;
  d: path("M10 5h7a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 19h-7c-1.039 0-1.992-.578-2.707-1.293l-4-4a2.414 2.414 0 0 1 0-3.414l4-4C8.008 5.578 8.961 5 10 5m3.707 4.293a.999.999 0 1 0-1.414 1.414L13.586 12l-1.293 1.293a.999.999 0 1 0 1.414 1.414L15 13.414l1.293 1.293a.999.999 0 1 0 1.414-1.414L16.414 12l1.293-1.293a.999.999 0 1 0-1.414-1.414L15 10.586Z");
}

</style>
