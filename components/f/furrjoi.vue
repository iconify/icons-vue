<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n3798ybel"/><path class="f5jw0kbgh"/><path class="v2sj87b7i"/><ellipse class="p6j2lccpc"/><path class="bwoy-jlpk"/><path class="sd0wgxz5j"/><circle class="v-8kefyih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:furrjoi" /></template>
<style>
.bwoy-jlpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.218 30.333C29.933 34.253 35.813 44 24 44m0-37.082c-6.145 0-13.137 1.683-13.137 16.834c0 9.161 4.993 9.018 5.65 15.594");
}

.f5jw0kbgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 6.918c6.145 0 13.137 1.683 13.137 16.834c0 9.161-4.994 9.018-5.651 15.594");
}

.n3798ybel {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.28 22.422h-1.05c-.67 0-1.214-.543-1.214-1.214v-4.077c0-.67.544-1.214 1.214-1.214h5.54c.67 0 1.214.544 1.214 1.214v4.077c0 .67-.544 1.214-1.215 1.214zm3.56-6.505v-1.756a1.845 1.845 0 0 0-1.836-1.846a1.847 1.847 0 0 0-1.846 1.846v1.756");
}

.p6j2lccpc {
  cx: 24px;
  cy: 41.404px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.602px;
  ry: 2.596px;
}

.sd0wgxz5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.197 18.525C8.724 14.993 5.86 5.6 7.897 4.185c1.8-1.252 8.885 4.26 8.885 4.26m0 21.888C18.067 34.253 12.187 44 24 44m-.001-21.578v-2.144");
}

.v-8kefyih {
  cx: 23.999px;
  cy: 19.17px;
  r: 1.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v2sj87b7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.803 18.525c2.473-3.532 5.339-12.924 3.3-14.34c-1.8-1.252-8.885 4.26-8.885 4.26");
}

</style>
