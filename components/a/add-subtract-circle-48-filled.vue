<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cf58oeb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-subtract-circle-48-filled" /></template>
<style>
.cf58oeb3b {
  fill: currentColor;
  d: path("M27.25 29.5a1.25 1.25 0 1 0 0 2.5h7.5a1.25 1.25 0 0 0 0-2.5zM24 44c11.046 0 20-8.954 20-20S35.046 4 24 4S4 12.954 4 24s8.954 20 20 20m0-2.5a17.43 17.43 0 0 1-11.46-4.273L37.228 12.54A17.43 17.43 0 0 1 41.5 24c0 9.665-7.835 17.5-17.5 17.5M12.25 17.25c0-.69.56-1.25 1.25-1.25h3v-2.75a1.25 1.25 0 0 1 2.5 0V16h2.75a1.25 1.25 0 1 1 0 2.5H19v2.75a1.25 1.25 0 1 1-2.5 0V18.5h-3c-.69 0-1.25-.56-1.25-1.25");
}

</style>
