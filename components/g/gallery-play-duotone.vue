<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hq185rwqp"/><path class="xhekpibku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-play-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hq185rwqp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 6C20.6569 6 22 7.34 22 9V19C22 20.66 20.6569 22 19 22H5C3.3432 22 2 20.66 2 19V9C2 7.34 3.3431 6 5 6H19ZM19 2C19.5523 2 20 2.45 20 3C20 3.55 19.5523 4 19 4H5C4.4477 4 4 3.55 4 3C4 2.45 4.4477 2 5 2H19Z");
}

.xhekpibku {
  d: path("M9.3477 10.24C9.8679 9.93 10.5628 9.9 11.1445 10.29L14.8965 12.85C15.7005 13.39 15.7003 14.61 14.8965 15.15L11.1445 17.71C10.5994 18.08 9.9024 18.05 9.3955 17.79C8.919 17.5 8.5407 16.89 8.502 16.29L8.5 11.77C8.5004 11.12 8.8361 10.55 9.3477 10.24Z");
}

</style>
