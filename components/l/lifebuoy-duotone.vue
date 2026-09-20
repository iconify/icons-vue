<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="awru1mmvj"/><path class="cmkmg82yj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lifebuoy-duotone" /></template>
<style>
.awru1mmvj {
  d: path("m195.88 195.88l-39.6-39.6a40 40 0 0 0 0-56.56l39.6-39.6a96 96 0 0 1 0 135.76M60.12 60.12a96 96 0 0 0 0 135.76l39.6-39.6a40 40 0 0 1 0-56.56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cmkmg82yj {
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m39.1 131.79a47.84 47.84 0 0 0 0-55.58l28.5-28.49a87.83 87.83 0 0 1 0 112.56ZM96 128a32 32 0 1 1 32 32a32 32 0 0 1-32-32m88.28-67.6l-28.49 28.5a47.84 47.84 0 0 0-55.58 0L71.72 60.4a87.83 87.83 0 0 1 112.56 0M60.4 71.72l28.5 28.49a47.84 47.84 0 0 0 0 55.58l-28.5 28.49a87.83 87.83 0 0 1 0-112.56M71.72 195.6l28.49-28.5a47.84 47.84 0 0 0 55.58 0l28.49 28.5a87.83 87.83 0 0 1-112.56 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
