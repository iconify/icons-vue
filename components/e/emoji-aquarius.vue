<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zghf5xbka"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-aquarius" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.zghf5xbka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.374 28.032s-.06-2.971-2.475-2.93c0 0-2.475-.018-2.475 2.791s-2.475 2.792-2.475 2.792c-2.415.04-2.474-2.9-2.474-2.9c0-2.84-2.475-2.822-2.475-2.822c-2.415-.04-2.475 2.89-2.475 2.89c0 2.83-2.475 2.812-2.475 2.812c-2.416.04-2.475-2.91-2.475-2.91c0-2.849-2.473-2.832-2.473-2.832c-2.417-.04-2.476 2.93-2.476 2.93m24.748-7.429s-.06-2.971-2.475-2.931c0 0-2.475-.017-2.475 2.792s-2.475 2.792-2.475 2.792c-2.415.04-2.474-2.9-2.474-2.9c0-2.84-2.475-2.822-2.475-2.822c-2.415-.04-2.475 2.89-2.475 2.89c0 2.829-2.475 2.812-2.475 2.812c-2.416.04-2.475-2.91-2.475-2.91c0-2.849-2.473-2.832-2.473-2.832c-2.417-.04-2.476 2.93-2.476 2.93");
}

</style>
