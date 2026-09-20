<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pemn838wn"/><path class="ia4sldbfw"/><path class="i-2dnzb7m"/><path class="nyd87ccoj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:data-export-user-outline-regular" /></template>
<style>
.i-2dnzb7m {
  d: path("M12 14v6");
}

.ia4sldbfw {
  d: path("M3 21a9 9 0 0 1 18 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nyd87ccoj {
  d: path("M9.5 16.5 12 14l2.5 2.5");
}

.pemn838wn {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
