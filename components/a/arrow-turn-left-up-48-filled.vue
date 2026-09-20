<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uan-_y6gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-left-up-48-filled" /></template>
<style>
.uan-_y6gx {
  fill: currentColor;
  d: path("M40.5 35a1.5 1.5 0 0 1 0 3h-18a7.5 7.5 0 0 1-7.5-7.5V13.121l-6.44 6.44a1.5 1.5 0 0 1-2.12-2.122l9-9a1.5 1.5 0 0 1 2.12 0l9 9a1.5 1.5 0 0 1-2.12 2.122L18 13.12V30.5a4.5 4.5 0 0 0 4.5 4.5z");
}

</style>
