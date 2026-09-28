<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="am_tatbtr"/><path class="szl-yc8bi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hockey-sticks-sharp-duotone" /></template>
<style>
.am_tatbtr {
  fill: currentColor;
  d: path("M3.4356 6.5569C3.1505 6.0875 2.9998 5.5488 2.9998 4.9996C2.9998 3.3427 4.3429 1.9996 5.9998 1.9996C7.0481 1.9996 8.0204 2.5468 8.5644 3.443L16.1882 16L19 16C20.6569 16 22 17.3431 22 19C22 20.6569 20.6569 22 19 22L13.3745 22C13.0251 22 12.7011 21.8176 12.5197 21.519L3.4356 6.5569Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.szl-yc8bi {
  stroke-opacity: 0.4;
  d: path("M14.0477 7.6559L14.3398 7.1749L16.2904 3.962C16.6531 3.3647 17.3012 3 18 3C19.1046 3 20 3.8954 20 5C20 5.366 19.8995 5.725 19.7096 6.0379L16.6795 11.0286L16.3875 11.5096M9.695 21L8.695 21L5 21C3.8954 21 3 20.1046 3 19C3 17.8954 3.8954 17 5 17L6.2664 17L7.2664 17");
}

</style>
