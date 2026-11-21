<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zmgev36dv"/><path class="zldfr90iq"/><path class="nd7_5xbuk"/><path class="c74aedcjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:biceps-flexed-broken" /></template>
<style>
.c74aedcjv {
  d: path("M9.78786 6.8307C8.30076 8.4 9.10076 12.2 8.22656 15.0268");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nd7_5xbuk {
  d: path("M7.40039 16C9.20039 13.4 12.4004 12.7 15.0004 14");
}

.zldfr90iq {
  d: path("M3.13086 10.2232C3.94976 6.2096 5.70416 2.5 9.60016 2.5C11.6002 2.5 12.8002 3.6 12.8002 5C12.8002 6.2 11.9002 7 10.7002 7C9.80016 7 9.20016 6.6 8.90016 6");
}

.zmgev36dv {
  d: path("M11.4634 13.4258C12.6004 10.6 14.8004 9.70001 17.0004 10C19.8004 10.4 21.6004 12.6 21.6004 15.3C21.6004 18.9 18.1004 21.5 12.8004 21.5C8.70039 21.5 5.10039 20.8 3.20039 19.3C2.60039 18.8 2.40039 18 2.40039 17.2C2.43999 16.2089 2.49929 15.0332 2.61799 13.7849");
}

</style>
