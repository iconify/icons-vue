<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0_p6m8by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-landscape-split-20-regular" /></template>
<style>
.c0_p6m8by {
  fill: currentColor;
  d: path("M16 16a2 2 0 0 0 2-2V9.414a1.5 1.5 0 0 0-.44-1.06l-3.914-3.915A1.5 1.5 0 0 0 12.586 4H4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2zm1-2a1 1 0 0 1-1 1h-6V5h2v3.5a1.5 1.5 0 0 0 1.5 1.5H17zM9 5v10H4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1zm4 3.5V5.207L16.793 9H13.5a.5.5 0 0 1-.5-.5");
}

</style>
