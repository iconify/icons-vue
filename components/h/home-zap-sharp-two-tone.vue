<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g9jji5bsi"/><path class="bhbr9n-_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-zap-sharp-two-tone" /></template>
<style>
.bhbr9n-_q {
  d: path("M13.3859 5.0748L12 3.9963L3 11L3 22L21 22L21 11M9 22L9 15L15 15L15 22M20.2929 1.7071L17 5L21 5L17.7071 8.2929");
}

.g9jji5bsi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 11L22 22C22 22.5523 21.5523 23 21 23L3 23C2.4477 23 2 22.5523 2 22L2 11C2 10.6915 2.1424 10.4003 2.3859 10.2108L11.3859 3.2071C11.747 2.926 12.253 2.926 12.6141 3.2071L14 4.2856L14 11L22 11Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
