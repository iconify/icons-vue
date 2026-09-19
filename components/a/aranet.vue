<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="amiqzx2ts"/><circle class="tr_s3nt2s"/><circle class="yumukqb0f"/><circle class="aq-z9ob2l"/><circle class="bs0ddxbnt"/><circle class="c9094zboz"/><circle class="fkg_87bxl"/><path class="f-u392bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aranet" /></template>
<style>
.amiqzx2ts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.286L4.5 40.714h39z");
}

.aq-z9ob2l {
  cx: 28.643px;
  cy: 22.143px;
  r: 0.929px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.bs0ddxbnt {
  cx: 32.357px;
  cy: 29.571px;
  r: 0.929px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.c9094zboz {
  cx: 37px;
  cy: 37px;
  r: 0.929px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f-u392bep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.794 27.064l-5.33 9.137m12.072-20.688l-5.34 9.146m.697.734l8.868-2.953m3.695 6.909l-12.61-3.158m17.355 10.354L18.707 26.544");
}

.fkg_87bxl {
  cx: 11px;
  cy: 37px;
  r: 0.929px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tr_s3nt2s {
  cx: 17.5px;
  cy: 25.857px;
  r: 1.393px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yumukqb0f {
  cx: 24px;
  cy: 14.714px;
  r: 0.929px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
