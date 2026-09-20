<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmch8p7ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:car-seat-off-rounded" /></template>
<style>
.zmch8p7ne {
  fill: currentColor;
  d: path("M9.325 6.5L6.5 3.7q.275-.325.663-.513T8 3q.825 0 1.413.588T10 5q0 .45-.175.838t-.5.662M9.15 18q-.725 0-1.263-.437T7.2 16.4l-1.1-5.35q-.1-.5 0-.95t.35-.85L2.1 4.9q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275l17 17q.275.275.275.7t-.275.7t-.7.275t-.7-.275L15.2 18z");
}

</style>
