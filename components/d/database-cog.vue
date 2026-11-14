<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fxtstrukg"/><path class="jk4-ebczb"/><path class="nj0f6lbmv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-cog" /></template>
<style>
.fxtstrukg {
  d: path("M13.267 21.215A23 23 0 0 1 12 21.25c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v7.255");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jk4-ebczb {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75q.652 0 1.277-.036m6.545-2.142q.177-.278.178-.572");
}

.nj0f6lbmv {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5m7.954 1.103l.001-.04a.53.53 0 0 1 .53-.516h.03a.53.53 0 0 1 .53.516l.001.04a.85.85 0 0 0 .425.715a.85.85 0 0 0 .832.011l.035-.019a.53.53 0 0 1 .711.201l.016.026a.53.53 0 0 1-.183.716l-.033.021a.85.85 0 0 0-.407.726a.85.85 0 0 0 .407.726l.033.021a.53.53 0 0 1 .183.716l-.016.026a.53.53 0 0 1-.711.201l-.035-.019a.85.85 0 0 0-.832.011a.85.85 0 0 0-.425.715l-.001.04a.53.53 0 0 1-.53.516h-.03a.53.53 0 0 1-.53-.516l-.001-.04a.85.85 0 0 0-.425-.715a.85.85 0 0 0-.832-.011l-.035.019a.53.53 0 0 1-.711-.201l-.016-.026a.53.53 0 0 1 .183-.716l.033-.021a.85.85 0 0 0 .407-.726a.85.85 0 0 0-.407-.726l-.033-.021a.53.53 0 0 1-.183-.716l.016-.026a.53.53 0 0 1 .711-.201l.035.019a.85.85 0 0 0 .832-.011a.85.85 0 0 0 .425-.715");
}

</style>
