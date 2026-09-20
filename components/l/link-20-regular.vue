<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="la3wwrqtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-20-regular" /></template>
<style>
.la3wwrqtc {
  fill: currentColor;
  d: path("M8 6a.5.5 0 0 1 .09.992L8 7H6a3 3 0 0 0-.197 5.994L6 13h2a.5.5 0 0 1 .09.992L8 14H6a4 4 0 0 1-.22-7.994L6 6zm6 0a4 4 0 0 1 .22 7.994L14 14h-2a.5.5 0 0 1-.09-.992L12 13h2a3 3 0 0 0 .197-5.994L14 7h-2a.5.5 0 0 1-.09-.992L12 6zM6 9.5h8a.5.5 0 0 1 .09.992L14 10.5H6a.5.5 0 0 1-.09-.992zh8z");
}

</style>
