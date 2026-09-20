<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct8yd04gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gamepad-down" /></template>
<style>
.ct8yd04gk {
  fill: currentColor;
  d: path("m12 9.077l-2-2V3h4v4.077zM16.923 14l-2-2l2-2H21v4zM3 14v-4h4.077l2 2l-2 2zm7 7v-4.077l2-2l2 2V21zm2-13.35l1-1V4h-2v2.65zM4 13h2.65l1-1l-1-1H4zm13.35 0H20v-2h-2.65l-1 1z");
}

</style>
