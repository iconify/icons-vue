<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piokwqfxs"/><path class="m1tyhaccm"/><g class="xtpeb-edw"><path class="ev0_0tb2v"/><path class="w0-ezmbxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:checkerboard-bold-duotone" /></template>
<style>
.ev0_0tb2v {
  d: path("M12 12V22C7.28626 22 4.92926 21.9999 3.46484 20.5361C2.00034 19.0711 2 16.714 2 12H12Z");
}

.m1tyhaccm {
  fill: currentColor;
  d: path("M12 12H2C2 7.286 2.00034 4.92887 3.46484 3.46387C4.92926 2.00011 7.28626 2 12 2V12Z");
}

.piokwqfxs {
  fill: currentColor;
  d: path("M22 12C22 16.714 21.9997 19.0711 20.5352 20.5361C19.0707 21.9999 16.7137 22 12 22V12H22Z");
}

.w0-ezmbxp {
  d: path("M12 2C16.7137 2 19.0707 2.00011 20.5352 3.46387C21.9997 4.92887 22 7.286 22 12H12V2Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
