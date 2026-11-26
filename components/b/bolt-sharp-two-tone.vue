<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l-zws9bbp"/><path class="ohyg7sc8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bolt-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l-zws9bbp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 12L22 17.2128C22 17.5826 21.7959 17.9222 21.4694 18.0958L12.4694 22.8807C12.3249 22.9575 12.1637 22.9977 12 22.9977C11.8363 22.9977 11.6751 22.9575 11.5306 22.8807L2.5306 18.0958C2.2041 17.9222 2 17.5826 2 17.2128L2 6.7872C2 6.4174 2.2041 6.0778 2.5306 5.9042L11.5306 1.1193C11.6751 1.0425 11.8363 1.0023 12 1.0023C12.1637 1.0023 12.3249 1.0425 12.4694 1.1193L21.4694 5.9042C21.7959 6.0778 22 6.4174 22 6.7872Z");
  stroke: none;
}

.ohyg7sc8q {
  d: path("M12 2.0023L21 6.7872L21 17.2128L12 21.9977L3 17.2128L3 6.7872ZM15 12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12C9 10.3431 10.3431 9 12 9C13.6569 9 15 10.3431 15 12Z");
}

</style>
