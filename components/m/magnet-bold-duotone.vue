<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frt5zby4n"/><g class="xtpeb-edw"><path class="e6j6dgbiz"/><path class="mgnw8cbbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnet-bold-duotone" /></template>
<style>
.e6j6dgbiz {
  d: path("M17 7H19.5C20.3284 7 21 6.32843 21 5.5V3.5C21 2.67157 20.3284 2 19.5 2H17V7Z");
}

.frt5zby4n {
  fill: currentColor;
  d: path("M17 2H13C7.47715 2 3 6.47715 3 12C3 17.5228 7.47715 22 13 22H17V17H13C10.2386 17 8 14.7614 8 12C8 9.23858 10.2386 7 13 7H17V2Z");
}

.mgnw8cbbw {
  d: path("M17 17V22H19.5C20.3284 22 21 21.3284 21 20.5V18.5C21 17.6716 20.3284 17 19.5 17H17Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
