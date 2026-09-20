<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="jerxe9ocu"/><path class="hrevw_blx"/><path class="to528to2t"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="kswphkyfs"/><path class="rgj9t7gfi"/><path class="g45hqpb0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:aggregation-window-duotone-regular" /></template>
<style>
.g45hqpb0s {
  d: path("M10.5 12h3");
}

.hrevw_blx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 7H16v10h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jerxe9ocu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 7H8v10h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kswphkyfs {
  d: path("M10.5 7H8v10h2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.rgj9t7gfi {
  d: path("M13.5 7H16v10h-2.5");
}

.to528to2t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
