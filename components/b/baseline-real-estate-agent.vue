<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqm04zbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-real-estate-agent" /></template>
<style>
.mqm04zbea {
  fill: currentColor;
  d: path("M1 22h4V11H1zm19-5h-7l-2.09-.73l.33-.94L13 16h2.82c.65 0 1.18-.53 1.18-1.18c0-.49-.31-.93-.77-1.11L8.97 11H7v9.02L14 22l8-3c-.01-1.1-.89-2-2-2M14 1.5l-7 5V9h2l8.14 3.26C18.26 12.71 19 13.79 19 15h2V6.5zm-.5 8.5h-1V9h1zm0-2h-1V7h1zm2 2h-1V9h1zm0-2h-1V7h1z");
}

</style>
