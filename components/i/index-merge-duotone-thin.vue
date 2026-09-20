<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j8_krc19t"/><path class="t6u-w0ajx"/><path class="b0batih_b"/><path class="c5h-9la_y"/><path class="h4_2qxb4z"/><path class="wo4w2lbba"/><path class="g3lrzsbos"/><path class="z_7v15bik"/><path class="cabegubdh"/><path class="ub1mcfbjy"/><path class="xpjur0b_h"/><path class="p0hi_9aen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-merge-duotone-thin" /></template>
<style>
.b0batih_b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c5h-9la_y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 9h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cabegubdh {
  d: path("M14 5h7");
}

.g3lrzsbos {
  d: path("M3 5h7");
}

.h4_2qxb4z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 11.5V14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8_krc19t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p0hi_9aen {
  d: path("M5 17h14");
}

.t6u-w0ajx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ub1mcfbjy {
  d: path("M14 9h7");
}

.wo4w2lbba {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 17h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xpjur0b_h {
  d: path("M12 11.5V14");
}

.z_7v15bik {
  d: path("M3 9h7");
}

</style>
