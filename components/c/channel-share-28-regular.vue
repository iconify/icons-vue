<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="bi6x3swgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-share-28-regular" /></template>
<style>
.bi6x3swgs {
  fill: currentColor;
  d: path("M6.75 3A3.75 3.75 0 0 0 3 6.75v7.5A3.75 3.75 0 0 0 6.75 18h7.42a3.001 3.001 0 1 0-.129-1.5H6.75a2.25 2.25 0 0 1-2.25-2.25v-7.5A2.25 2.25 0 0 1 6.75 4.5h7.5a2.25 2.25 0 0 1 2.25 2.25v.5a.75.75 0 0 0 1.5 0v-.5A3.75 3.75 0 0 0 14.25 3zM17 15.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-3.041-4h7.291a2.25 2.25 0 0 1 2.25 2.25v7.5a2.25 2.25 0 0 1-2.25 2.25h-7.5a2.25 2.25 0 0 1-2.25-2.25v-.5a.75.75 0 0 0-1.5 0v.5A3.75 3.75 0 0 0 13.75 25h7.5A3.75 3.75 0 0 0 25 21.25v-7.5A3.75 3.75 0 0 0 21.25 10h-7.42a3.001 3.001 0 1 0 .129 1.5M9.5 11a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0");
}

</style>
