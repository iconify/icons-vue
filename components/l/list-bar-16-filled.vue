<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hxu1ddcce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:list-bar-16-filled" /></template>
<style>
.hxu1ddcce {
  fill: currentColor;
  d: path("M6 14h6.75c.69 0 1.25-.56 1.25-1.25v-.5c0-.69-.56-1.25-1.25-1.25H6zm0-4h6.75c.69 0 1.25-.56 1.25-1.25v-1.5C14 6.56 13.44 6 12.75 6H6zM5 6v4H3.25C2.56 10 2 9.44 2 8.75v-1.5C2 6.56 2.56 6 3.25 6zm1-1h6.75C13.44 5 14 4.44 14 3.75v-.5C14 2.56 13.44 2 12.75 2H6zM5 2v3H3.25C2.56 5 2 4.44 2 3.75v-.5C2 2.56 2.56 2 3.25 2zm0 9v3H3.25C2.56 14 2 13.44 2 12.75v-.5c0-.69.56-1.25 1.25-1.25z");
}

</style>
