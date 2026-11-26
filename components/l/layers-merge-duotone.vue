<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j0wvr5b5b"/><path class="m234k1h3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-merge-duotone" /></template>
<style>
.j0wvr5b5b {
  stroke-opacity: 0.4;
  d: path("M2 12.625L11.5618 17.2864C11.8384 17.4212 12.1616 17.4212 12.4382 17.2864L22 12.625M2 17.2375L11.5618 21.8989C11.8384 22.0337 12.1616 22.0337 12.4382 21.8989L22 17.2375");
}

.m234k1h3m {
  d: path("M12 2V13M8 9L12 13L16 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
