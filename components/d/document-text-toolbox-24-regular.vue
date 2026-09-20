<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qymkpib4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-text-toolbox-24-regular" /></template>
<style>
.qymkpib4m {
  fill: currentColor;
  d: path("M10.813 13a2.76 2.76 0 0 0-1.416-1.5h5.853a.75.75 0 0 1 0 1.5zm.778 1.25c.614.298 1.087.84 1.295 1.5h2.364a.75.75 0 0 0 0-1.5zM15.25 17H13v1.5h2.25a.75.75 0 0 0 0-1.5M5.5 4v7.25h-.75q-.392.001-.75.104V4a2 2 0 0 1 2-2h6.172c.515 0 1.047.22 1.413.586l5.829 5.828A2 2 0 0 1 20 9.828V20a2 2 0 0 1-2 2h-5.05q.05-.243.05-.5v-1h5a.5.5 0 0 0 .5-.5V10H14a2 2 0 0 1-2-2V3.5H6a.5.5 0 0 0-.5.5m11.878 4.5L13.5 4.621V8a.5.5 0 0 0 .5.5zM3 15h-.5A1.5 1.5 0 0 0 1 16.5V18h2.5v-.25a.75.75 0 0 1 1.5 0V18h3v-.25a.75.75 0 0 1 1.5 0V18H12v-1.5a1.5 1.5 0 0 0-1.5-1.5H10v-1a1.75 1.75 0 0 0-1.75-1.75h-3.5A1.75 1.75 0 0 0 3 14zm1.5-1a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v1h-4zM1 21.5v-2h2.5v.75a.75.75 0 0 0 1.5 0v-.75h3v.75a.75.75 0 0 0 1.5 0v-.75H12v2a1.5 1.5 0 0 1-1.5 1.5h-8A1.5 1.5 0 0 1 1 21.5");
}

</style>
