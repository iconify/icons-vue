<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tgcg89bdo"/><path class="stdmb7bil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bandage-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.stdmb7bil {
  d: path("M16.0294 3L21 7.9706L7.9706 21L3 16.0294L16.0294 3ZM12 7.0294L16.9706 12M7.0294 12L12 16.9706");
}

.tgcg89bdo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.7365 2.2929L21.7071 7.2635C21.8946 7.451 22 7.7053 22 7.9706C22 8.2358 21.8946 8.4901 21.7071 8.6777L8.6777 21.7071C8.4901 21.8946 8.2358 22 7.9706 22C7.7053 22 7.451 21.8946 7.2635 21.7071L2.2929 16.7365C2.1054 16.549 2 16.2947 2 16.0294C2 15.7642 2.1054 15.5099 2.2929 15.3223L15.3223 2.2929C15.5099 2.1054 15.7642 2 16.0294 2C16.2947 2 16.549 2.1054 16.7365 2.2929Z");
  stroke: none;
}

</style>
