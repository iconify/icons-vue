<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dxyzmpz-u"/><path class="dnjvc_rqb"/><path class="kr8frt1sq"/><path class="n1vhvxs_b"/><path class="xfnw69i_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fishing-rod-line-duotone" /></template>
<style>
.dnjvc_rqb {
  d: path("M4.69922 8.24999V3.94999C4.69922 2.94999 5.3 2.34998 6.3 2.34998M4.70078 8.24998C5.47398 8.24998 6.10078 9.14538 6.10078 10.25C6.10078 11.3546 5.47398 12.25 4.70078 12.25C3.92758 12.25 3.30078 11.3546 3.30078 10.25C3.30078 9.14538 3.92758 8.24998 4.70078 8.24998M4.69922 12.25V17.45C4.69922 18.9964 5.95282 20.25 7.49922 20.25C9.04562 20.25 10.2992 18.9964 10.2992 17.45V15.05L8.49922 16.65");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.dxyzmpz-u {
  d: path("M6.30078 2.34998C14.1008 2.34998 19.3008 6.24998 19.3008 12.85V16.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kr8frt1sq {
  d: path("M17.9004 18.95V17.65C17.9004 16.99 17.9004 16.6601 18.1054 16.455C18.3105 16.25 18.6404 16.25 19.3004 16.25C19.9604 16.25 20.2903 16.25 20.4954 16.455C20.7004 16.6601 20.7004 16.99 20.7004 17.65V20.25C20.7004 20.91 20.7004 21.2399 20.4954 21.445C20.2903 21.65 19.9604 21.65 19.3004 21.65C18.6404 21.65 18.3105 21.65 18.1054 21.445C17.9004 21.2399 17.9004 20.91 17.9004 20.25V18.95Z");
}

.n1vhvxs_b {
  d: path("M17.6004 13.65C17.6004 14.8098 16.6602 15.75 15.5004 15.75C14.3406 15.75 13.4004 14.8098 13.4004 13.65C13.4004 12.4902 14.3406 11.55 15.5004 11.55C16.6602 11.55 17.6004 12.4902 17.6004 13.65Z");
}

.xfnw69i_q {
  d: path("M17.5996 13.65H19.2996");
}

</style>
