<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qjdumzd8h"/><path class="hs8eys0gu"/><circle class="tr7nzyz6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:magic-home" /></template>
<style>
.hs8eys0gu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.206 19.447l3.117-3.118l6.249 6.25m-1.994-10.701c1.57-1.996 4.339-3.21 7.321-3.21c2.98 0 5.748 1.212 7.318 3.206m-12.364 2.457a6.93 6.93 0 0 1 5.046-2.17c1.915 0 3.744.787 5.046 2.17m-7.69 2.593c.778-.773 1.7-1.188 2.644-1.188s1.866.415 2.644 1.188");
}

.qjdumzd8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.075 39.332H8.57v-13.92H5.5l9.834-9.836l7.004 7.005H42.5");
}

.tr7nzyz6c {
  cx: 33.899px;
  cy: 19.495px;
  r: 0.75px;
  fill: currentColor;
}

</style>
