<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yn7g0eb0x"/><path class="mwtrac3la"/><path class="lafvrhbzd"/><path class="x-9-pn30c"/><path class="t51ob8p-s"/><path class="jl7dsy5_j"/><path class="bt4mvqbkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bicycle-broken" /></template>
<style>
.bt4mvqbkp {
  d: path("M18.3493 15.475L15.3338 5.6399L15.3336 5.63944C15.2232 5.27915 15.168 5.09895 15.2508 4.987C15.3336 4.875 15.5222 4.875 15.8993 4.875H17.9993");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jl7dsy5_j {
  d: path("M6.90039 5.17499H9.90039");
}

.lafvrhbzd {
  d: path("M5.65039 15.4749C6.80039 11.0749 8.40039 8.7749 11.0004 8.7749H16.2962");
}

.mwtrac3la {
  d: path("M21.9992 15.475C21.9992 17.4908 20.365 19.125 18.3492 19.125C16.3334 19.125 14.6992 17.4908 14.6992 15.475C14.6992 13.4592 16.3334 11.825 18.3492 11.825C20.365 11.825 21.9992 13.4592 21.9992 15.475Z");
}

.t51ob8p-s {
  d: path("M8.30078 5.17499L9.24568 9.19459");
}

.x-9-pn30c {
  d: path("M5.65039 15.4749H8.30039C9.71459 15.4749 10.4217 15.4749 11.1237 15.1227C11.8255 14.7706 12.248 14.204 13.0929 13.071L13.0937 13.0699L16.2962 8.7749");
}

.yn7g0eb0x {
  d: path("M4.6759 11.9564C4.986 11.8708 5.3127 11.825 5.65 11.825C7.6658 11.825 9.3 13.4592 9.3 15.475C9.3 17.4908 7.6658 19.125 5.65 19.125C3.6342 19.125 2 17.4908 2 15.475C2 14.9399 2.1152 14.4316 2.3221 13.9737");
}

</style>
