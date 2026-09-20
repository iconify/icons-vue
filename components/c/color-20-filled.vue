<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sid7wnrjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-20-filled" /></template>
<style>
.sid7wnrjh {
  fill: currentColor;
  d: path("M10 2a8 8 0 0 1 3.388 15.249a3.77 3.77 0 0 1-3.291-.059c-.973-.503-1.696-1.467-1.648-2.731c.017-.445.082-.867.143-1.243c.063-.387.118-.712.137-1.015c.017-.297-.005-.533-.079-.732c-.07-.191-.2-.381-.45-.569c-.313-.234-.58-.275-.844-.237c-.3.043-.615.188-1.015.387c-.735.365-1.776.942-2.974.332c-1.102-.562-1.424-1.868-1.22-2.917A8 8 0 0 1 10 2m2.5 11a1 1 0 1 0 0 2a1 1 0 0 0 0-2m2-2.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2m0-3a1 1 0 1 0 0 2a1 1 0 0 0 0-2m-2-2.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2m-3-1a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
