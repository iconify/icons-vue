<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dt16vxbca"/><path class="u2uojcbap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layer-mask-off-two-tone" /></template>
<style>
.dt16vxbca {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.6465 20.6465C20.1443 20.8736 19.5869 21 19 21L5 21C2.7909 21 1 19.2091 1 17L1 7C1 5.3778 1.9657 3.9812 3.3535 3.3535ZM22.7071 17.0502L8.9498 3.2929C9.1308 3.1119 9.3808 3 9.6569 3L19 3C21.2091 3 23 4.7909 23 7L23 16.3431C23 16.6193 22.8881 16.8693 22.7071 17.0502Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u2uojcbap {
  d: path("M4.1292 4.1292C2.8646 4.5128 2 5.6786 2 7L2 17C2 18.6569 3.3431 20 5 20L19 20C19.295 20 19.5885 19.9565 19.8708 19.8708M9.6569 4L19 4C20.6569 4 22 5.3431 22 7L22 16.3431M14.8284 14.8284C14.0783 15.5786 13.0609 16 12 16C9.7909 16 8 14.2091 8 12C8 10.9391 8.4214 9.9217 9.1716 9.1716M2 2L22 22");
}

</style>
