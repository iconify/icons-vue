<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jbk7lzb9f"/><path class="zpvo49dam"/><path class="l3yb7ybjz"/><path class="mdp-r2mfo"/><path class="mbzvimb-r"/><path class="tjvfebbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drain-duotone-regular" /></template>
<style>
.jbk7lzb9f {
  fill: currentColor;
  d: path("M8 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l3yb7ybjz {
  d: path("M2 9h6");
}

.mbzvimb-r {
  d: path("M12 14v5");
}

.mdp-r2mfo {
  d: path("M16 9h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tjvfebbkf {
  d: path("M9.5 16.5 12 19l2.5 -2.5");
}

.zpvo49dam {
  d: path("M8 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
