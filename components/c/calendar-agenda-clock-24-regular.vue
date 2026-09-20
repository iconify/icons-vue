<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvo-xvlhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-agenda-clock-24-regular" /></template>
<style>
.pvo-xvlhh {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m.25-9A3.25 3.25 0 0 1 21 6.25v5.774a6.5 6.5 0 0 0-1.5-.71V6.25a1.75 1.75 0 0 0-1.75-1.75H6.25A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75h5.065a6.4 6.4 0 0 0 .71 1.5H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zm-.25 11a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5H20a.5.5 0 0 0 0-1h-2v-2.5a.5.5 0 0 0-.5-.5m-6.185 1.5q-.234.718-.294 1.5H7.75a.75.75 0 0 1-.102-1.493l.102-.007zm4.402-4.25a6.5 6.5 0 0 0-2.652 1.5H7.75a.75.75 0 0 1-.102-1.493l.102-.007zM16.25 7a.75.75 0 0 1 .102 1.493l-.102.007h-8.5a.75.75 0 0 1-.102-1.493L7.75 7z");
}

</style>
