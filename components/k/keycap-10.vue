<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vxonir6if"/><path class="l-31-qbep"/><path class="m8de_ixuf"/><path class="c2zm1-coq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:keycap-10" /></template>
<style>
.c2zm1-coq {
  fill: var(--svg-color--fff, #fff);
  d: path("m29.02 45.39l5.66-.53v41.67h-4.22c-.56 0-1.01.46-1.01 1.02v14.09c0 .56.45 1.01 1.01 1.01h22.72c.56 0 1.02-.46 1.02-1.01V87.55c0-.56-.45-1.02-1.02-1.02h-4.22V26.09c0-.3-.13-.59-.36-.78s-.54-.28-.83-.22l-19.03 3.44c-.48.09-.83.51-.83 1v14.84c0 .29.12.56.33.75c.21.2.48.3.78.27m52.42 57.74c13.68 0 22.53-15.41 22.53-39.26c0-14.18-3.14-25.34-8.55-32.09c-3.69-4.6-8.43-7.18-13.98-7.18c-13.68 0-22.52 15.41-22.52 39.27c0 1.61.05 3.17.13 4.7c1.09 21.15 9.63 34.56 22.39 34.56m-7.67-49.46c1.35-6.68 4.1-10.75 7.67-10.75c.82 0 1.59.24 2.31.65c3.83 2.16 6.28 9.76 6.28 20.29c0 12.52-3.45 20.94-8.59 20.94s-8.59-8.41-8.59-20.94c0-3.82.33-7.26.92-10.19");
}

.l-31-qbep {
  fill: var(--svg-color--f79329, #f79329);
  d: path("M124.48 3.52L3.52 124.48C5.7 126.65 8.7 128 12 128h104c6.6 0 12-5.4 12-12V12c0-3.3-1.35-6.3-3.52-8.48");
}

.m8de_ixuf {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M112 101c0 6.63-5.37 12-12 12H27.89c-6.6 0-12-5.4-12-12V28.9c0-6.6 5.4-12 12-12H100c6.63 0 12 5.37 12 12z");
}

.vxonir6if {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M116 128H12c-6.6 0-12-5.4-12-12V12C0 5.4 5.4 0 12 0h104c6.6 0 12 5.4 12 12v104c0 6.6-5.4 12-12 12");
}

</style>
