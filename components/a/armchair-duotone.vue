<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n-ght0t4z"/><path class="xcvmqtbqd"/><path class="xvq6pwott"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:armchair-duotone" /></template>
<style>
.n-ght0t4z {
  fill: currentColor;
  d: path("M3 10.1707L3 7C3 3.6863 5.6863 1 9 1L15 1C18.3137 1 21 3.6863 21 7L21 10.1707C20.6872 10.0601 20.3506 10 20 10C18.3431 10 17 11.3431 17 13L7 13C7 11.3431 5.6569 10 4 10C3.6494 10 3.3128 10.0601 3 10.1707Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xcvmqtbqd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 21L19 21C21.2092 21 23 19.2092 23 17L23 13C23 11.3431 21.6569 10 20 10C18.3431 10 17 11.3431 17 13L7 13C7 11.3431 5.6569 10 4 10C2.3431 10 1 11.3431 1 13L1 17C1 19.2092 2.7908 21 5 21Z");
  stroke: none;
}

.xvq6pwott {
  d: path("M19 20V22M5 20V22");
}

</style>
