<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gmk9o9b1o"/><path class="irudeebhr"/><path class="k3sddyo-g"/><path class="jr2f22bmk"/><path class="qh-vgybrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:letter-opened-line-duotone" /></template>
<style>
.gmk9o9b1o {
  d: path("M18 6.10168C19.3001 6.22957 20.1752 6.51858 20.8284 7.17176C22 8.34334 22 10.229 22 14.0002C22 17.7714 22 19.657 20.8284 20.8286C19.6569 22.0002 17.7712 22.0002 14 22.0002H10C6.22876 22.0002 4.34315 22.0002 3.17157 20.8286C2 19.657 2 17.7714 2 14.0002C2 10.229 2 8.34334 3.17157 7.17176C3.82475 6.51858 4.69989 6.22957 6 6.10168");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irudeebhr {
  d: path("M10 6H14");
}

.jr2f22bmk {
  d: path("M7.43926 11.1994L8.1589 11.7991C9.99553 13.3296 10.9139 14.0949 12 14.0949C13.0861 14.0949 14.0045 13.3296 15.8411 11.7991L16.5607 11.1994C17.2685 10.6096 17.6224 10.3147 17.8112 9.91156C18 9.50842 18 9.04778 18 8.1265V7C18 4.64298 18 3.46447 17.2678 2.73223C16.5355 2 15.357 2 13 2H11C8.64298 2 7.46447 2 6.73223 2.73223C6 3.46447 6 4.64298 6 7V8.1265C6 9.04778 6 9.50842 6.18882 9.91156C6.37764 10.3147 6.73152 10.6096 7.43926 11.1994Z");
}

.k3sddyo-g {
  d: path("M11 9H13");
}

.qh-vgybrh {
  d: path("M6 10L8.1589 11.7991C9.99553 13.3296 10.9139 14.0949 12 14.0949C13.0861 14.0949 14.0045 13.3296 15.8411 11.7991L18 10");
}

</style>
