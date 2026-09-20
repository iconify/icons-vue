<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q646-yz3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:board-48-regular" /></template>
<style>
.q646-yz3b {
  fill: currentColor;
  d: path("M35.75 6A6.25 6.25 0 0 1 42 12.25v23.5A6.25 6.25 0 0 1 35.75 42h-23.5A6.25 6.25 0 0 1 6 35.75v-23.5A6.25 6.25 0 0 1 12.25 6zM8.5 35.75a3.75 3.75 0 0 0 3.75 3.75H23v-20H8.5zm17-4.75v8.5h10.25a3.75 3.75 0 0 0 3.75-3.75V31zm0-2.5h14V12.25a3.75 3.75 0 0 0-3.75-3.75H25.5zm-13.25-20a3.75 3.75 0 0 0-3.75 3.75V17H23V8.5z");
}

</style>
