<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn-2ygbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:first-page-outline-rounded" /></template>
<style>
.yn-2ygbvt {
  fill: currentColor;
  d: path("M6.288 17.713Q6 17.425 6 17V7q0-.425.288-.712T7 6t.713.288T8 7v10q0 .425-.288.713T7 18t-.712-.288M13.8 12l3.9 3.9q.275.275.275.7t-.275.7t-.7.275t-.7-.275l-4.6-4.6q-.15-.15-.212-.325T11.425 12t.063-.375t.212-.325l4.6-4.6q.275-.275.7-.275t.7.275t.275.7t-.275.7z");
}

</style>
