<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llhp5r44e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fast-forward-bulk-round" /></template>
<style>
.llhp5r44e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.543 6.428L11 9.101V9a3 3 0 0 1 4.543-2.572l5 3a2.998 2.998 0 0 1 0 5.144l-5 3A2.998 2.998 0 0 1 11 15v-.101l-4.457 2.673A2.998 2.998 0 0 1 2 15V9a3 3 0 0 1 4.543-2.572");
}

</style>
