<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkh6f026t"/><path class="lo-jzcbdp"/><path class="h3__u3b3s"/><path class="v2deczw2f"/><path class="k6nj2fbya"/><path class="bg2ejdbaq"/><path class="b1ja9gnou"/><path class="z0kumyy5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:double-entry-duotone-regular" /></template>
<style>
.b1ja9gnou {
  d: path("M5 10h4.5");
}

.bg2ejdbaq {
  d: path("M12 5v16");
}

.h3__u3b3s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 10h4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.lo-jzcbdp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mkh6f026t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v2deczw2f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 14H19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z0kumyy5w {
  d: path("M14.5 14H19");
}

</style>
