<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_iotmi0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:extension-off" /></template>
<style>
.o_iotmi0b {
  fill: currentColor;
  d: path("M20 17.15L6.85 4h1.2q.175-1.275 1.15-2.137T11.5 1q1.3 0 2.275.863T14.95 4H18q.825 0 1.413.588T20 6v3.35q.9.45 1.45 1.3T22 12.5q0 1.025-.55 1.875T20 15.65zm.475 6.175l-19.8-19.8L2.1 2.1l19.8 19.8zM5 21q-.85 0-1.425-.575T3 19v-3.8q1.2 0 2.1-.762T6 12.5q0-1.15-.9-1.9T3 9.8V4l17 17z");
}

</style>
