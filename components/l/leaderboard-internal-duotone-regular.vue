<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xg4fy3qiq"/><path class="qzd33790h"/><path class="ozbpihsrq"/><path class="ear4nsbqw"/><path class="g7go0l5ag"/><path class="wew0vnk_n"/><path class="j6riv-b4h"/><path class="w0e70wbbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:leaderboard-internal-duotone-regular" /></template>
<style>
.ear4nsbqw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g7go0l5ag {
  d: path("M5 11v8");
}

.j6riv-b4h {
  d: path("M19 14v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozbpihsrq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 14v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qzd33790h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w0e70wbbt {
  d: path("M3 21.5h18");
}

.wew0vnk_n {
  d: path("M12 5v14");
}

.xg4fy3qiq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
