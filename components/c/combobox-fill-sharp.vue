<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlksaabgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:combobox-fill-sharp" /></template>
<style>
.hlksaabgr {
  fill: currentColor;
  d: path("M21 2a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1ZM8 6a1 1 0 0 0-2 0v2a1 1 0 0 0 2 0Zm6.707-.707a.999.999 0 1 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l2-2a.999.999 0 1 0-1.414-1.414L16 6.586ZM21 14a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1Zm-4 3H7a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2");
}

</style>
