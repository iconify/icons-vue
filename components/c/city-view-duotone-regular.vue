<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cu5aslbqx"/><path class="kls5wpc7q"/><path class="fcix6zbfn"/><path class="bb6tr_t8k"/><path class="lbkuffism"/><path class="hb_6svr8j"/><path class="bi34yzw-v"/><path class="urzumpb2c"/><path class="qowfo405a"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:city-view-duotone-regular" /></template>
<style>
.bb6tr_t8k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bi34yzw-v {
  d: path("M12 21V4h7v17");
}

.cu5aslbqx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21V10h7v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fcix6zbfn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 14h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hb_6svr8j {
  d: path("M3 21V10h7v11");
}

.kls5wpc7q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 21V4h7v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lbkuffism {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.qowfo405a {
  d: path("M12 9h7");
}

.urzumpb2c {
  d: path("M3 14h7");
}

</style>
