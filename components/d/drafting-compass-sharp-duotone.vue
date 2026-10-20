<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dhs3y6blk"/><path class="qsy8ab34k"/><path class="af93n7t7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:drafting-compass-sharp-duotone" /></template>
<style>
.af93n7t7l {
  fill: currentColor;
  d: path("M15 6C15 7.6569 13.6569 9 12 9C10.3431 9 9 7.6569 9 6C9 4.3431 10.3431 3 12 3C13.6569 3 15 4.3431 15 6Z");
  stroke: none;
}

.dhs3y6blk {
  stroke-opacity: 0.4;
  d: path("M21.25 13.6538L21 13.9373C18.722 16.5203 15.444 18 12 18C8.556 18 5.278 16.5203 3 13.9373L2.75 13.6538");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qsy8ab34k {
  d: path("M12 1L12 4M11.1984 7.8323L4.7379 22.5992M12.8016 7.8323L19.2621 22.5992");
}

</style>
