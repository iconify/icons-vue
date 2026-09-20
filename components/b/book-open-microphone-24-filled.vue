<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik-73ub-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-microphone-24-filled" /></template>
<style>
.ik-73ub-v {
  fill: currentColor;
  d: path("M22.25 16a.75.75 0 0 1 .75.75a4.75 4.75 0 0 1-4 4.69v.81a.75.75 0 0 1-1.5 0v-.81a4.75 4.75 0 0 1-4-4.69a.75.75 0 0 1 1.5 0a3.25 3.25 0 0 0 6.5 0a.75.75 0 0 1 .75-.75M10 4c.768 0 1.47.289 2 .764A3 3 0 0 1 14 4h6a2 2 0 0 1 2 2v9.02a1.8 1.8 0 0 0-.5.15v-.92c0-1.15-.598-2.16-1.5-2.738V6h-6a1 1 0 0 0-1 1v8.526c-.309.316-.5.747-.5 1.224c0 1.186.36 2.287.975 3.202A3 3 0 0 1 12 19.236A3 3 0 0 1 10 20H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2zm8.25 8a2.25 2.25 0 0 1 2.25 2.25v2.5a2.25 2.25 0 0 1-4.5 0v-2.5A2.25 2.25 0 0 1 18.25 12M4 18h6a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1H4z");
}

</style>
