<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aiu47l_9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-diagonal-up-right-48-regular" /></template>
<style>
.aiu47l_9f {
  fill: currentColor;
  d: path("M38.75 24c-.69 0-1.25-.56-1.25-1.25V12.268L20.472 29.296a8 8 0 1 1-1.768-1.768L35.733 10.5H25.25a1.25 1.25 0 1 1 0-2.5h13.5c.69 0 1.25.56 1.25 1.25v13.5c0 .69-.56 1.25-1.25 1.25M14 39.5a5.5 5.5 0 1 0 0-11a5.5 5.5 0 0 0 0 11");
}

</style>
