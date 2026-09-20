<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="int5d5yju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fastfood-sharp" /></template>
<style>
.int5d5yju {
  fill: currentColor;
  d: path("M2.442 15.385q0-2.187 2.064-3.209t4.552-1.022t4.552 1.022t2.063 3.209zm0 3.307v-1h13.231v1zm0 3.308v-1h13.231v1zm15.231 0v-6.61q0-2.355-1.757-3.93q-1.758-1.575-4.16-2.064l-.429-3.011h4.615v-4h1v4h4.616L19.95 22z");
}

</style>
