<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="o4h2qsblv"/><path class="l5p4aoa1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:crown-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l5p4aoa1n {
  d: path("M230.9 73.6a15.85 15.85 0 0 0-18.9 3.79l-33.67 36.29l-35.8-80.29a1 1 0 0 1 0-.1a16 16 0 0 0-29.06 0a1 1 0 0 1 0 .1l-35.8 80.29L44 77.39a16 16 0 0 0-27.75 13.42c0 .11 0 .21.07.32L39 195a16 16 0 0 0 15.72 13h146.57A16 16 0 0 0 217 195l22.68-103.87c0-.11 0-.21.07-.32a15.85 15.85 0 0 0-8.85-17.21m-29.55 118.08l-.06.32H54.71l-.06-.32L32 88l.14.16l42 45.24a8 8 0 0 0 13.18-2.18L128 40l40.69 91.25a8 8 0 0 0 13.18 2.18l42-45.24l.13-.19Z");
}

.o4h2qsblv {
  d: path("m231.87 89.42l-22.7 104a8 8 0 0 1-7.88 6.61H54.71a8 8 0 0 1-7.88-6.61l-22.7-104A8 8 0 0 1 38 82.76L80 128l40.74-91.35a8 8 0 0 1 14.52 0L176 128l42-45.24a8 8 0 0 1 13.87 6.66");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
