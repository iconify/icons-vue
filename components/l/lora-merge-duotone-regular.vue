<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="itr6ywumz"/><path class="atxxk_b2f"/><path class="w122ipbuy"/><path class="udqwuzb_t"/><path class="hdlchkb0j"/><path class="dfxjcnksd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lora-merge-duotone-regular" /></template>
<style>
.atxxk_b2f {
  fill: currentColor;
  d: path("M17.5 10.5a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dfxjcnksd {
  d: path("m16 10 -2 2 2 2");
}

.hdlchkb0j {
  d: path("M14.5 12H17");
}

.itr6ywumz {
  fill: currentColor;
  d: path("M3 6a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
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

.udqwuzb_t {
  d: path("M17.5 10.5a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

.w122ipbuy {
  d: path("M3 6a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
