<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4qq4fbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-mac-outline-rounded" /></template>
<style>
.p4qq4fbdh {
  fill: currentColor;
  d: path("M10 18H4q-.825 0-1.412-.587T2 16V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v11q0 .825-.587 1.413T20 18h-6l1.85 1.85q.05.05.15.35v.3q0 .2-.15.35t-.35.15H8.35q-.15 0-.25-.1t-.1-.25v-.5q0-.05.1-.25zm-6-5h16V5H4zm0 0V5z");
}

</style>
