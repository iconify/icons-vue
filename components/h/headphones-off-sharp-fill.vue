<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uoztf63xy"/><path class="gf2jrs6ep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headphones-off-sharp-fill" /></template>
<style>
.gf2jrs6ep {
  d: path("M3 13L3 12C3 9.5147 4.0074 7.2647 5.636 5.636M8.1779 3.788L9.1256 3.4688C10.0282 3.1648 10.9949 3 12 3C16.9706 3 21 7.0294 21 12L21 13M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uoztf63xy {
  fill: currentColor;
  d: path("M2 12C2 10.4812 3.4812 9 5 9L7 9C7.5523 9 8 9.4477 8 10L8 21C8 21.5523 7.5523 22 7 22L5 22C3.4812 22 2 20.5188 2 19L2 12ZM19 22L17 22C16.4477 22 16 21.5523 16 21L16 17L17 17L21.1213 21.1213C20.5784 21.6642 19.8284 22 19 22ZM16 12.3431L16 10C16 9.4477 16.4477 9 17 9L19 9C20.5188 9 22 10.4812 22 12L22 16.3431L20.5858 16.3431L16.5858 12.3431L16 12.3431Z");
  stroke: none;
}

</style>
