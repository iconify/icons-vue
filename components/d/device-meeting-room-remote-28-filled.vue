<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="f4d1_ccfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-remote-28-filled" /></template>
<style>
.f4d1_ccfs {
  fill: currentColor;
  d: path("M8.351 3a3.5 3.5 0 0 0-3.377 2.58l-1.216 4.457Q3.998 10 4.25 10h4.5a3.25 3.25 0 0 1 3.251 3.25V21h9.996c2.638 0 4.554-2.508 3.86-5.052L23.029 5.579A3.5 3.5 0 0 0 19.652 3zm3.64 21q.01-.124.01-.25V22.5h8.25a.75.75 0 1 1 0 1.5zm-5.49-7a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3M2 13.25A2.25 2.25 0 0 1 4.25 11h4.5A2.25 2.25 0 0 1 11 13.25v10.5A2.25 2.25 0 0 1 8.75 26h-4.5A2.25 2.25 0 0 1 2 23.75zm2.25-.75a.75.75 0 0 0-.75.75v10.5c0 .414.336.75.75.75h4.5a.75.75 0 0 0 .75-.75v-10.5a.75.75 0 0 0-.75-.75z");
}

</style>
