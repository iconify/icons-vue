<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="wkw772orw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:elgato-stream-deck-mobile" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wkw772orw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.874 14.5l2.165 1.25v2.5L9.874 19.5l-2.165-1.25v-2.5zm7.063 0l2.165 1.25v2.5l-2.165 1.25l-2.165-1.25v-2.5zm7.063 0l2.165 1.25v2.5L24 19.5l-2.165-1.25v-2.5zm7.063 0l2.165 1.25v2.5l-2.165 1.25l-2.165-1.25v-2.5zm7.063 0l2.165 1.25v2.5l-2.165 1.25l-2.165-1.25v-2.5zm-28.252 7l2.165 1.25v2.5L9.874 26.5l-2.165-1.25v-2.5zm7.075 0l2.165 1.25v2.5L16.95 26.5l-2.165-1.25v-2.5zm7.051 0l2.165 1.25v2.5L24 26.5l-2.165-1.25v-2.5zm7.098 0l2.165 1.25v2.5l-2.165 1.25l-2.165-1.25v-2.5zm7.075 0l2.165 1.25v2.5l-2.165 1.25l-2.165-1.25v-2.5zm-28.299 7l2.165 1.25v2.5L9.874 33.5l-2.165-1.25v-2.5zm7.069 0l2.165 1.25v2.5l-2.165 1.25l-2.165-1.25v-2.5zm7.057 0l2.165 1.25v2.5L24 33.5l-2.165-1.25v-2.5zm7.081 0l2.165 1.25v2.5l-2.165 1.25l-2.165-1.25v-2.5zm7.068 0l2.165 1.25v2.5L38.15 33.5l-2.165-1.25v-2.5z");
}

</style>
