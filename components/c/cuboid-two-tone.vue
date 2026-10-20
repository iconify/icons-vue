<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nfecdbcwz"/><path class="pt_wshbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cuboid-two-tone" /></template>
<style>
.nfecdbcwz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.2929 7.2929L7 2.5858C7.3751 2.2107 7.8838 2 8.4142 2L21 2C21.5523 2 22 2.4477 22 3L22 15.5858C22 16.1162 21.7893 16.6249 21.4142 17L16.7071 21.7071C16.5196 21.8946 16.2652 22 16 22L4 22C2.8954 22 2 21.1046 2 20L2 8C2 7.7348 2.1054 7.4804 2.2929 7.2929Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pt_wshbts {
  d: path("M3 8L7.7071 3.2929C7.8946 3.1054 8.149 3 8.4142 3L21 3L21 15.5858C21 15.851 20.8946 16.1054 20.7071 16.2929L16 21L4 21C3.4477 21 3 20.5523 3 20L3 8ZM3 8L16 8L16 21M16 8L21 3");
}

</style>
