<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usno92urd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:basketball-backboard" /></template>
<style>
.usno92urd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.375 1.75H5.625q-1.398 0-2.386.989q-.989.988-.989 2.386v4.75q0 1.398.989 2.386q.988.989 2.386.989h.781l1.864 7.92v.002l.01.04l.006.017q.044.137.136.249t.219.18l.002.002q.167.09.357.09h6q.191 0 .359-.092q.028-.015.054-.032q.111-.073.19-.18t.117-.234v-.001l.01-.039v-.001l1.864-7.921h.781q3.375 0 3.375-3.375v-4.75q0-3.375-3.375-3.375m-3.656 17.169l-2.061-3.778q-.105-.194-.299-.299q-.131-.072-.279-.088t-.292.026t-.259.136t-.187.225l-2.061 3.778l-1.334-5.669h8.106zm-4.456 1.331L12 17.066l1.737 3.184zM13.5 4.75q2.25 0 2.25 2.25v1q0 2.25-2.25 2.25h-3q-2.25 0-2.25-2.25V7q0-2.25 2.25-2.25z");
}

</style>
