<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3-pp08xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lobster" /></template>
<style>
.y3-pp08xl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 8.5h4.5a.75.75 0 0 1 .75.8l-.55 7.45h-4.9L9 9.3a.75.75 0 0 1 .75-.8m-.45 3.75h5.4M9.45 14.5h5.1m-4.2 4.5h3.3q.6 0 .93.5l.84 1.25q.33.5-.27.5h-6.3q-.6 0-.27-.5l.84-1.25q.33-.5.93-.5m-.85-9l-2-1.5m7 1.5l2-1.5m-9.77-.54L3.77 6.29Q3.25 6 3.3 5.4l.15-2.05q.05-.6.48-.18l1.04 1.01q.43.42.71-.11l.29-.54q.28-.53.61-.03l1.34 2q.33.5.09 1.05L7.49 7.7q-.24.55-.76.26m10.54 0l2.96-1.67q.52-.29.47-.89l-.15-2.05q-.05-.6-.48-.18l-1.04 1.01q-.43.42-.71-.11l-.29-.54q-.28-.53-.61-.03l-1.34 2q-.33.5-.09 1.05l.52 1.15q.24.55.76.26");
}

</style>
