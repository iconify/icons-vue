<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zjfasgbxn"/><path class="q7tkkubef"/><path class="d9nb1lnep"/><path class="uh5a45b0l"/><path class="xgkt50b4f"/><path class="zwfc0tbtb"/><path class="h26bvabki"/><path class="e8mk-vdvn"/><path class="y5k8b5bfa"/><path class="wskxlyzso"/><path class="tuynf1bdi"/><path class="mhila7bcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:debounce-duotone-regular" /></template>
<style>
.d9nb1lnep {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e8mk-vdvn {
  d: path("M6 9v6");
}

.h26bvabki {
  d: path("M3 9v6");
}

.mhila7bcl {
  d: path("M20 7v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q7tkkubef {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tuynf1bdi {
  d: path("m15 10 2 2 -2 2");
}

.uh5a45b0l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wskxlyzso {
  d: path("M12 12h3");
}

.xgkt50b4f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y5k8b5bfa {
  d: path("M9 9v6");
}

.zjfasgbxn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zwfc0tbtb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
