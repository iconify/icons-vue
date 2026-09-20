<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cuso263ot"/><path class="ezik40n3m"/><path class="yz--0hb6q"/><path class="ikxao0-um"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/><path class="bdxedv3gx"/><path class="i4nkkkbsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:exam-timer-duotone-regular" /></template>
<style>
.bdxedv3gx {
  d: path("M6 3v3l6 6 6 -6V3");
}

.cuso263ot {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 3h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ezik40n3m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i4nkkkbsh {
  d: path("M6 21v-3l6 -6 6 6v3");
}

.ikxao0-um {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 21v-3l6 -6 6 6v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rjrs_5bsc {
  d: path("M6 3h12");
}

.xslfg2evh {
  d: path("M6 21h12");
}

.yz--0hb6q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 3v3l6 6 6 -6V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
