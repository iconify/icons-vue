<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lezwc4bvo"/><path class="lnw92ebsc"/><path class="qude_sb_h"/><path class="c0qm6tbuu"/><path class="yivx5zbth"/><path class="ar5_4pb4n"/><path class="h26bvabki"/><path class="e8mk-vdvn"/><path class="y5k8b5bfa"/><path class="wskxlyzso"/><path class="tuynf1bdi"/><path class="mhila7bcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:debounce-duotone-bold" /></template>
<style>
.ar5_4pb4n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c0qm6tbuu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e8mk-vdvn {
  d: path("M6 9v6");
}

.h26bvabki {
  d: path("M3 9v6");
}

.lezwc4bvo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lnw92ebsc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mhila7bcl {
  d: path("M20 7v10");
}

.qude_sb_h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tuynf1bdi {
  d: path("m15 10 2 2 -2 2");
}

.wskxlyzso {
  d: path("M12 12h3");
}

.y5k8b5bfa {
  d: path("M9 9v6");
}

.yivx5zbth {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
