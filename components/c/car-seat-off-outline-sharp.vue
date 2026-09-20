<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruu06xbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:car-seat-off-outline-sharp" /></template>
<style>
.ruu06xbnh {
  fill: currentColor;
  d: path("M9.325 6.5L6.5 3.7q.275-.325.663-.513T8 3q.825 0 1.413.588T10 5q0 .45-.175.838t-.5.662M21.2 21.2l-1.4 1.4l-4.6-4.6H9.15q-.725 0-1.263-.437T7.2 16.4l-1.1-5.35q-.1-.5 0-.95t.35-.85L1.4 4.2l1.4-1.4z");
}

</style>
