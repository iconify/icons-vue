<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wsswtccxx"/><path class="xh_6qo5jd"/><path class="ea_vsab9a"/><path class="kez1s6byc"/><path class="zg42pabnh"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flag-off-broken" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.ea_vsab9a {
  d: path("M5 7.8V5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kez1s6byc {
  d: path("M5 14L7.4707 13.5059C9.1212 13.1758 10.8321 13.3328 12.3949 13.958C13.0772 14.2309 13.787 14.4144 14.5073 14.5073");
}

.wsswtccxx {
  d: path("M5 22V14");
}

.xh_6qo5jd {
  d: path("M5 14.0002V11.2002");
}

.zg42pabnh {
  d: path("M17.7651 14.3089L17.937 14.2659C18.5621 14.1096 19.0006 13.548 19.0006 12.9037V5.53672C19.0006 4.75612 18.2671 4.18342 17.5098 4.37272C15.8786 4.78052 14.1603 4.66392 12.5992 4.03942L12.3955 3.95802C10.8327 3.33282 9.12178 3.17582 7.47128 3.50592L7.04688 3.59072");
}

</style>
