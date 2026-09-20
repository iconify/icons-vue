<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pxhnn12iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:contract-up-right-20-regular" /></template>
<style>
.pxhnn12iq {
  fill: currentColor;
  d: path("M4 6a2 2 0 0 1 2-2h4v4a2 2 0 0 0 2 2h4v4a2 2 0 0 1-2 2h-2.5a.5.5 0 0 0 0 1H14a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3H6a3 3 0 0 0-3 3v2.5a.5.5 0 0 0 1 0zm8 3a1 1 0 0 1-1-1V4h3a2 2 0 0 1 2 2v3zm-9 2.5a.5.5 0 0 0 .5.5h3.793l-4.147 4.146a.5.5 0 0 0 .708.708L8 12.707V16.5a.5.5 0 0 0 1 0v-5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0-.5.5");
}

</style>
