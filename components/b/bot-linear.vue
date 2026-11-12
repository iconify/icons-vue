<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="jqg1wpbhz"/><path class="y8s1yox1j"/><path class="r3lhriy2l"/><circle class="t2k6t0buo"/><path class="u-kdhybkb"/><path class="tcxv1qbqd"/><path class="pwdaeoc-i"/><ellipse class="b0opclfzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bot-linear" /></template>
<style>
.b0opclfzv {
  cx: 9px;
  cy: 13.5px;
  rx: 0.5px;
  ry: 1px;
}

.jqg1wpbhz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.9458 12.5732C20.5207 12.6331 20.9393 12.7418 21.268 12.9391C22.0003 13.3784 22.0003 14.0855 22.0003 15.4997C22.0003 16.9139 22.0003 17.621 21.268 18.0604C20.9393 18.2576 20.5207 18.3663 19.9458 18.4262");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.pwdaeoc-i {
  d: path("M15.5 13.5C15.5 14.0523 15.2761 14.5 15 14.5C14.7239 14.5 14.5 14.0523 14.5 13.5C14.5 12.9477 14.7239 12.5 15 12.5C15.2761 12.5 15.5 12.9477 15.5 13.5Z");
}

.r3lhriy2l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.4 22H13.6C16.617 22 18.1255 22 19.0627 21.0481C19.6369 20.4649 19.8594 19.664 19.9455 18.4265C20 17.644 20 16.6869 20 15.5C20 14.3131 20 13.356 19.9455 12.5735C19.8594 11.336 19.6369 10.5351 19.0627 9.9519C18.1255 9 16.617 9 13.6 9H10.4C7.38301 9 5.87452 9 4.93726 9.9519C4.36306 10.5351 4.14064 11.336 4.05448 12.5735C4 13.356 4 14.3131 4 15.5C4 16.6869 4 17.644 4.05448 18.4265C4.14064 19.664 4.36306 20.4649 4.93726 21.0481C5.87452 22 7.38301 22 10.4 22Z");
}

.t2k6t0buo {
  cx: 12px;
  cy: 3.5px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tcxv1qbqd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 18C9.85038 18.6303 10.8846 19 12 19C13.1154 19 14.1496 18.6303 15 18");
}

.u-kdhybkb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5V9");
}

.y8s1yox1j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.05448 18.4262C3.47962 18.3663 3.06096 18.2576 2.73223 18.0604C2 17.621 2 16.9139 2 15.4997C2 14.0855 2 13.3784 2.73223 12.9391C3.06096 12.7418 3.47962 12.6331 4.05448 12.5732");
}

</style>
