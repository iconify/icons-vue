<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gklh-gfbx"/><path class="wt2sl3biy"/><path clip-rule="evenodd" class="q0mjolbzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hard-drive-duotone" /></template>
<style>
.gklh-gfbx {
  stroke-opacity: 0.4;
  d: path("M2.4954 12.3486L4.1448 6.8506C4.6524 5.1587 6.2097 4 7.9761 4L16.0239 4C17.7903 4 19.3476 5.1587 19.8552 6.8506L21.5046 12.3486");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q0mjolbzu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 10L19 10C21.2091 10 23 11.7909 23 14L23 17C23 19.2091 21.2091 21 19 21L5 21C2.7909 21 1 19.2091 1 17L1 14C1 11.7909 2.7909 10 5 10ZM19 15.5C19 14.6716 18.3284 14 17.5 14C16.6716 14 16 14.6716 16 15.5C16 16.3284 16.6716 17 17.5 17C18.3284 17 19 16.3284 19 15.5Z");
  stroke: none;
}

.wt2sl3biy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 15.5C19 16.3284 18.3284 17 17.5 17C16.6716 17 16 16.3284 16 15.5C16 14.6716 16.6716 14 17.5 14C18.3284 14 19 14.6716 19 15.5Z");
  stroke: none;
}

</style>
