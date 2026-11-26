<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eagptma9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-not" /></template>
<style>
.eagptma9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.4856 6.1258L17.4856 11.1258C17.8031 11.3022 18 11.6368 18 12C18 12.3632 17.8031 12.6978 17.4856 12.8742L8.4856 17.8742C8.3371 17.9567 8.1699 18 8 18C7.4477 18 7 17.5523 7 17L7 7C7 6.4477 7.4477 6 8 6C8.1699 6 8.3371 6.0433 8.4856 6.1258ZM2 12L7 12M18 12C18 10.8954 18.8954 10 20 10C21.1046 10 22 10.8954 22 12C22 13.1046 21.1046 14 20 14C18.8954 14 18 13.1046 18 12Z");
}

</style>
