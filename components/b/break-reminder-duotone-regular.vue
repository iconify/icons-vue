<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="is-hszdcp"/><path class="w6vhwfb1w"/><path class="uaw1f0vcp"/><path class="j2-dy8bux"/><path class="r57e8zbzz"/><path class="ng_tlibuk"/><path class="s0v-_1bji"/><path class="v9hia4w8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:break-reminder-duotone-regular" /></template>
<style>
.is-hszdcp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 9v9h11V9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j2-dy8bux {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ng_tlibuk {
  d: path("M15 9a3 3 0 0 1 0 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r57e8zbzz {
  d: path("M4 9v9h11V9");
}

.s0v-_1bji {
  d: path("M7 3a3 3 0 0 1 0 6");
}

.uaw1f0vcp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v9hia4w8h {
  d: path("M12 3a3 3 0 0 1 0 6");
}

.w6vhwfb1w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 9a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
