<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hutzx8bpl"/><path class="zk5koz2uj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-crack-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hutzx8bpl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 2C19.8256 2 23 4.98233 23 8.75C23 11.6443 21.418 13.9747 19.4219 15.9922C17.4582 17.9769 14.8378 19.8917 12.6494 21.7607C12.2754 22.08 11.7246 22.08 11.3506 21.7607C9.16223 19.8917 6.54178 17.9769 4.57812 15.9922C2.58202 13.9747 1 11.6443 1 8.75C1 4.98233 4.17445 2 8 2C9.4851 2 10.828 2.4608 12 3.25391C13.172 2.4608 14.5149 2 16 2Z");
  stroke: none;
}

.zk5koz2uj {
  d: path("M12 4.5L10.5 8.75L13 9.5L11 13L13 15L13.2929 15.2929");
}

</style>
