<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mzsthfbrb"/><path class="nzpsuduik"/><path class="ae-e09b3w"/><path class="lfxwg8kjz"/><path class="nz_ew84gn"/><path class="blzbt67pp"/><path class="ih6mqvbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bookshelf-duotone-regular" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.blzbt67pp {
  d: path("M14 14v5");
}

.ih6mqvbrd {
  d: path("M17 14v5");
}

.lfxwg8kjz {
  d: path("M7 5v5");
}

.mzsthfbrb {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nz_ew84gn {
  d: path("M10 5v5");
}

.nzpsuduik {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
