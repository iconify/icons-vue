<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hqs3z7wnn"/><path class="pk9hfwbjl"/><path class="vs45k5xrt"/><path class="im40qnp0k"/><path class="k4qo1xe9v"/><path class="hu2mwjewo"/><path class="l46p6bckm"/><path class="zka_zabrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bar-stool-duotone-regular" /></template>
<style>
.hqs3z7wnn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hu2mwjewo {
  d: path("M12 6v10");
}

.im40qnp0k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k4qo1xe9v {
  d: path("M4 6h16");
}

.l46p6bckm {
  d: path("m8 20 4 -4 4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pk9hfwbjl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vs45k5xrt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 20 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zka_zabrc {
  d: path("M9 13h6");
}

</style>
