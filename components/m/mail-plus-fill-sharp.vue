<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca0t062il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-plus-fill-sharp" /></template>
<style>
.ca0t062il {
  fill: currentColor;
  d: path("M19 9a1 1 0 0 1-2 0V7h-2a1 1 0 0 1 0-2h2V3a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2h-2Zm-5.568 1H9.414l-6-6H11a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779A6 6 0 0 0 13.432 10M4 7.414l4.293 4.293A1 1 0 0 0 9 12h6c.26 0 .51-.102.697-.283c.981.489 2.083.778 3.184.739a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5.414Z");
}

</style>
