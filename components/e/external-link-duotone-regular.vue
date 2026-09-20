<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wau-_xbhd"/><path class="o-1ay8bqc"/><path class="nio10abwq"/><path class="zww0vqboc"/><path class="bc7uaebvz"/><path class="b5rbpxbdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:external-link-duotone-regular" /></template>
<style>
.b5rbpxbdb {
  d: path("M14 4h6v6");
}

.bc7uaebvz {
  d: path("m12 12 8 -8");
}

.nio10abwq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 4h6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o-1ay8bqc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 12 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wau-_xbhd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 6H4v14h14v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zww0vqboc {
  d: path("M10 6H4v14h14v-6");
}

</style>
