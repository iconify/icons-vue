<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dfqhfq-4w"/><path class="sxr9t17bs"/><path class="i-b1b9mbj"/><path class="a3h8xnbto"/><path class="e8q-s-qwm"/><path class="feaejwetu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cash-out-broken" /></template>
<style>
.a3h8xnbto {
  d: path("M9 20.5H15C16.8856 20.5 17.8284 20.5 18.4142 19.9142C19 19.3284 19 18.3856 19 16.5V10.5C19 8.61438 19 7.67157 18.4142 7.08579C17.8284 6.5 16.8856 6.5 15 6.5H9C7.11438 6.5 6.17157 6.5 5.58579 7.08579C5 7.67157 5 8.61438 5 10.5V16.5C5 18.3856 5 19.3284 5.58579 19.9142C6.17157 20.5 7.11438 20.5 9 20.5Z");
}

.dfqhfq-4w {
  d: path("M5.88889 3.5C3.74111 3.5 2 5.29998 2 7.52036C2 9.42457 3.28058 11.0196 5 11.4352");
}

.e8q-s-qwm {
  stroke-linejoin: round;
  d: path("M5 17.5H13.0047");
}

.feaejwetu {
  stroke-linejoin: round;
  d: path("M17.0107 17.5H18.9998");
}

.i-b1b9mbj {
  stroke-linejoin: round;
  d: path("M12 6.5V13.5M10 11.1667L12 13.5L14 11.1667");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sxr9t17bs {
  d: path("M19 11.4352C20.7194 11.0196 22 9.42457 22 7.52036C22 5.29998 20.2589 3.5 18.1111 3.5H10.0049");
}

</style>
