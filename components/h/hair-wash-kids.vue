<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f__o5vchk"/><path class="myj1c2buo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-wash-kids" /></template>
<style>
.f__o5vchk {
  d: path("M12 21.5V19c-1.5-1-2-2.5-2-4c0-2.75 2-4.5 4.5-4.5c2.25 0 4.25 1.5 4.25 4l.75 2c.25.25 0 .75-.5.75h-.25v1.25c0 .75-.75 1.25-1.25 1.25h-1.25v1.75");
}

.myj1c2buo {
  d: path("M7.5 11L3 6.5L6.5 3L11 7.5c2 0 3.5 1 3.5 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
