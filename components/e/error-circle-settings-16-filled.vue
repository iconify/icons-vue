<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yg90mzb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:error-circle-settings-16-filled" /></template>
<style>
.yg90mzb0r {
  fill: currentColor;
  d: path("M11.255 9.227a2 2 0 0 0 2.557.026c.305.123.588.288.842.487a2 2 0 0 0 1.302 2.201a3.5 3.5 0 0 1 .025.915l-.032.01a2 2 0 0 0-1.407 2.437l.009.033a3.5 3.5 0 0 1-.806.435a2 2 0 0 0-2.557-.027a3.5 3.5 0 0 1-.842-.486a2 2 0 0 0-1.302-2.201a3.5 3.5 0 0 1-.025-.916l.032-.01a2 2 0 0 0 1.407-2.436l-.009-.033c.246-.178.517-.326.806-.435M7 0a7 7 0 0 1 6.89 8.22a4.5 4.5 0 0 0-5.67 5.67c-.397.07-.804.11-1.22.11A7 7 0 1 1 7 0m5.5 11.749a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M7 9a.75.75 0 1 0 0 1.5A.75.75 0 0 0 7 9m0-5.5a.5.5 0 0 0-.5.5v3.5l.008.09A.5.5 0 0 0 7.5 7.5V4l-.008-.09A.5.5 0 0 0 7 3.5");
}

</style>
