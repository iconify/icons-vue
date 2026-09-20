<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="atz95bbsm"/><path class="qa-jr78us"/><path class="vdu53hb5w"/><path class="jje0epbum"/><path class="kfdmhd64i"/><path class="e4btx4zel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flaky-test-duotone-regular" /></template>
<style>
.atz95bbsm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 7 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e4btx4zel {
  d: path("m21 15 -6 6");
}

.jje0epbum {
  d: path("m3 7 3 3 5 -5");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qa-jr78us {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vdu53hb5w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 15 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
