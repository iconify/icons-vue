<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u2a4cniii"/><circle class="bpls5sbrx"/><circle class="ignyr_l1n"/><path class="bikn7mbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:confused-face" /></template>
<style>
.bikn7mbvu {
  fill: currentColor;
  d: path("M43.27 41.832c-5.766-1.549-12.049-.428-16.93 3.013c-1.205.87 1.053 4.028 2.252 3.153c3.223-2.268 8.352-3.835 13.66-2.432c1.422.376 2.535-3.309 1.018-3.734");
}

.bpls5sbrx {
  cx: 42.383px;
  cy: 24.683px;
  r: 5px;
  fill: currentColor;
}

.ignyr_l1n {
  cx: 19.732px;
  cy: 28.676px;
  r: 4.999px;
  fill: currentColor;
}

.u2a4cniii {
  fill: currentColor;
  d: path("M61.539 26.797C58.974 12.239 46.316 2 32.031 2c-1.73 0-3.482.15-5.246.461C10.471 5.338-.425 20.895 2.452 37.215C5.018 51.772 17.677 62.01 31.961 62.01c1.729 0 3.482-.15 5.244-.461c16.316-2.877 27.213-18.432 24.334-34.752M54.523 47.78c-4.213 6.016-10.518 10.031-17.752 11.307c-1.592.28-3.21.423-4.811.423c-13.351 0-24.726-9.559-27.047-22.729C2.281 21.848 12.288 7.556 27.22 4.923c1.591-.28 3.21-.423 4.812-.423c13.35 0 24.725 9.56 27.047 22.731c1.275 7.235-.343 14.533-4.556 20.549");
}

</style>
