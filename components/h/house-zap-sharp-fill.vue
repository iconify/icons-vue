<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="vzh39mb7o"/><path class="phae_1bft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-zap-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.phae_1bft {
  d: path("M19.2929 1.7071L19 2L16 5L20 5L17 8L16.7071 8.2929");
}

.vzh39mb7o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.3857 3.20703C11.7469 2.92599 12.253 2.92599 12.6142 3.20703L13 3.50684V11H21V22C20.9998 22.5521 20.5521 23 20 23H16V19C16 16.7909 14.2091 15 12 15C9.79088 15 7.99996 16.7909 7.99996 19V23H3.99996C3.44782 23 3.00016 22.5521 2.99996 22V12.2666L2.22848 12.8672L0.999962 11.2891L11.3857 3.20703Z");
  stroke: none;
}

</style>
