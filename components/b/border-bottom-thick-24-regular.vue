<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_lpbbb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-bottom-thick-24-regular" /></template>
<style>
.j_lpbbb_q {
  fill: currentColor;
  d: path("M14 3.75a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h2.5a.75.75 0 0 1 .75.75m-9.5 7a.75.75 0 0 0-1.5 0v2.5a.75.75 0 0 0 1.5 0zm15 0a.75.75 0 0 1 1.5 0v2.5a.75.75 0 0 1-1.5 0zM6.25 3a.75.75 0 0 1 0 1.5h-.5c-.69 0-1.25.56-1.25 1.25v.5a.75.75 0 0 1-1.5 0v-.5A2.75 2.75 0 0 1 5.75 3zM17 3.75a.75.75 0 0 1 .75-.75h.5A2.75 2.75 0 0 1 21 5.75v.5a.75.75 0 0 1-1.5 0v-.5c0-.69-.56-1.25-1.25-1.25h-.5a.75.75 0 0 1-.75-.75M3 18a1 1 0 1 1 2 0a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1a1 1 0 1 1 2 0a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3");
}

</style>
