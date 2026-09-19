<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-14.058 16.35 31.905)" class="yyk9ekb-g"/><path class="x6zy__bll"/><path class="u6aq5xbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kingdom-two-crowns" /></template>
<style>
.u6aq5xbmh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.135 15.276c1.6 1.093 2.544 1.99 2.337 3.18l-1.49 8.554M30.606 12.047c1.187-.011 2.471.095 3.792.325s2.565.564 3.678.976m-15.108 6.5l.839-4.822c.202-1.186 1.398-1.707 3.269-2.199m-2.749 9.847c1.64 1.157 4.475 2.218 7.793 2.796c3.742.646 7.117.511 8.959-.221M30.606 12.048l-.872 5.006a18 18 0 0 0-3.422.161l.764-4.388m14.059 2.449l-.764 4.388a18 18 0 0 0-3.167-1.308l.872-5.008");
}

.x6zy__bll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.498 19.095c1.906.35 3.132.786 3.426 1.958l2.11 8.423m-19.38-6.915c-1.515 1.207-2.392 2.17-2.099 3.342l2.11 8.423m2.9-13.91c1.08-.492 2.296-.916 3.597-1.242s2.573-.525 3.757-.6M7.438 32.503c1.891.601 5.268.49 8.954-.433s6.716-2.416 8.1-3.838M9.565 20.416l1.235 4.93c-1.189.469-2.224 1-3.063 1.535l-1.082-4.32m13.843-3.466l1.082 4.32a18 18 0 0 0-3.425.09l-1.235-4.93m8.42 8.12c1.63.8 3.8 1.476 6.23 1.9c5.439.945 10.097.241 10.415-1.582c.097-.569-.24-1.176-.906-1.765c-1.485-1.32-4.62-2.584-8.361-3.24c-3.472-.607-6.626-.53-8.535.077");
}

.yyk9ekb-g {
  cx: 16.35px;
  cy: 31.904px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.983px;
  ry: 3.342px;
}

</style>
