<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-3f3u0ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-bottom-24-regular" /></template>
<style>
.h-3f3u0ky {
  fill: currentColor;
  d: path("M2.75 21a.75.75 0 0 1 0-1.5h18.5a.75.75 0 0 1 0 1.5zM4 15.75A2.25 2.25 0 0 0 6.25 18h2.5A2.25 2.25 0 0 0 11 15.75V5.25A2.25 2.25 0 0 0 8.75 3h-2.5A2.25 2.25 0 0 0 4 5.25zm2.25.75a.75.75 0 0 1-.75-.75V5.25a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-.75.75zm6.75-.75A2.25 2.25 0 0 0 15.25 18h2.5A2.25 2.25 0 0 0 20 15.75v-7a2.25 2.25 0 0 0-2.25-2.25h-2.5A2.25 2.25 0 0 0 13 8.75zm2.25.75a.75.75 0 0 1-.75-.75v-7a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 .75.75v7a.75.75 0 0 1-.75.75z");
}

</style>
