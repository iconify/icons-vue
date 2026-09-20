<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="unc2k4bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-20-filled" /></template>
<style>
.unc2k4bgq {
  fill: currentColor;
  d: path("M14 6a4 4 0 0 1 .2 7.995L14 14h-2a.75.75 0 0 1-.102-1.493L12 12.5h2a2.5 2.5 0 0 0 .164-4.995L14 7.5h-2a.75.75 0 0 1-.102-1.493L12 6zM8 6a.75.75 0 0 1 .102 1.493L8 7.5H6a2.5 2.5 0 0 0-.164 4.995L6 12.5h2a.75.75 0 0 1 .102 1.493L8 14H6a4 4 0 0 1-.2-7.995L6 6zM6.25 9.25h7.5a.75.75 0 0 1 .102 1.493l-.102.007h-7.5a.75.75 0 0 1-.102-1.493zh7.5z");
}

</style>
