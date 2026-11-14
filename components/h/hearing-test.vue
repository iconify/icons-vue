<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d_nzmcbuz"/><path class="y6543hbto"/><path class="hc_qufb7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hearing-test" /></template>
<style>
.d_nzmcbuz {
  d: path("M2.5 9c0-3.5 2.5-6 6-6C11.75 3 14 5.5 14 8.75c0 2.75-1.5 4-2.75 5.25S10 16.5 9.5 18.5C9 20.25 7.5 21 6 21c-2 0-3.5-1.5-3.5-3.5");
}

.hc_qufb7w {
  d: path("M19.975 5.375a13.25 13.25 0 0 1 0 13.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6543hbto {
  d: path("M5.5 9c0-1.75 1.25-3 3-3s2.75 1.25 2.75 2.75m4.213-1.625a8.5 8.5 0 0 1 0 9.75m2.252-11.328a11.25 11.25 0 0 1 0 12.906");
}

</style>
