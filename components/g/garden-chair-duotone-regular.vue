<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="es_gwdbvn"/><path class="f9t4f0nhw"/><path class="gxmqsnbdz"/><path class="zwicszbqt"/><path class="rsue96bcd"/><path class="q5jw2tb7h"/><path class="aut8y9hmn"/><path class="gwt34irsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:garden-chair-duotone-regular" /></template>
<style>
.aut8y9hmn {
  d: path("M7 12v7");
}

.es_gwdbvn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f9t4f0nhw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 12 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gwt34irsi {
  d: path("M15 12v7");
}

.gxmqsnbdz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q5jw2tb7h {
  d: path("m17 12 4 -4");
}

.rsue96bcd {
  d: path("M5 12h12");
}

.zwicszbqt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
