<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lr66sscyo"/><path class="pen5ukb_h"/><path class="im40qnp0k"/><path class="cfwhgr43a"/><path class="t0-mwc0xy"/><path class="zka_zabrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:emergency-room-duotone-regular" /></template>
<style>
.cfwhgr43a {
  d: path("M4 20v-8a8 8 0 0 1 16 0v8");
}

.im40qnp0k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lr66sscyo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20v-8a8 8 0 0 1 16 0v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pen5ukb_h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t0-mwc0xy {
  d: path("M12 10v6");
}

.zka_zabrc {
  d: path("M9 13h6");
}

</style>
