<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aan20hb4l"/><path class="zdbqvzt9f"/><path class="df_t0x8bu"/><path class="z-6zmuoeb"/><path class="coen3fbth"/><path class="s6lrl6bmb"/><path class="xwfp38btc"/><path class="mfc7nxp-y"/><path class="ag9m5ebdy"/><path class="kp83gfxow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fasting-duotone-regular" /></template>
<style>
.aan20hb4l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 4v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ag9m5ebdy {
  d: path("M12 7v13");
}

.coen3fbth {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20 16 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.df_t0x8bu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kp83gfxow {
  d: path("M4 20 16 8");
}

.mfc7nxp-y {
  d: path("M9 7h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s6lrl6bmb {
  d: path("M9 4v3");
}

.xwfp38btc {
  d: path("M15 4v3");
}

.z-6zmuoeb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zdbqvzt9f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 4v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
