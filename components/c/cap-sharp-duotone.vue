<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mu_f3pbye"/><path class="l45vxtbke"/><path class="cxbz5cbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cap-sharp-duotone" /></template>
<style>
.cxbz5cbdc {
  fill: currentColor;
  d: path("M17.2952 12.5243C19.0344 12.8722 20.7394 13.3914 22.3846 14.0769C22.7573 14.2322 23 14.5963 23 15L23 19.5C23 20.8808 21.8806 22 20.5 22C20.1261 22 19.7569 21.9162 19.4195 21.7545C17.1036 20.6445 14.5682 20.0683 12 20.0683C9.4318 20.0683 6.8964 20.6445 4.5805 21.7545C4.2431 21.9162 3.8739 22 3.5 22C2.1194 22 1 20.8808 1 19.5L1 15C1 14.5963 1.2427 14.2322 1.6154 14.0769C4.9059 12.7058 8.4353 12 12 12C13.7824 12 15.5559 12.1765 17.2952 12.5243Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l45vxtbke {
  d: path("M12 3L12 13");
}

.mu_f3pbye {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.26 4.8927C6.2561 3.0962 8.9954 2 12 2C15.0046 2 17.7439 3.0962 19.74 4.8927C21.7378 6.6907 23 9.2022 23 12L23 15C23 15.5523 22.5523 16 22 16C21.868 16 21.7372 15.9739 21.6154 15.9231C18.5687 14.6536 15.3007 14 12 14C8.6993 14 5.4313 14.6536 2.3846 15.9231C2.2628 15.9739 2.132 16 2 16C1.4477 16 1 15.5523 1 15L1 12C1 9.2022 2.2622 6.6907 4.26 4.8927Z");
  stroke: none;
}

</style>
