<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jascrv2te"/><path class="u8yx54bbk"/><path class="b-l1siqcl"/><path class="dpyqrkbsr"/><path class="js6p-gbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cardmindreader" /></template>
<style>
.b-l1siqcl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.836 34.396s-3.572-9.97-13.087-12.853M41.546 31.71a21.2 21.2 0 0 0-10.43-11.775m11.247 9.353s-3.219-7.968-8.6-10.47m9.205 7.677s-2.323-5.832-6.726-8.755M24 23.968a36.5 36.5 0 0 1-4.334 5.518c-3.249 3.602-2.947 5.923-2.947 5.923a3.23 3.23 0 0 0 2.42 3.517a2.385 2.385 0 0 0 2.669-.832l.991-1.61s.724 4.21-1.78 5.647");
}

.dpyqrkbsr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.019 42.131A10 10 0 0 1 24 41.617m0-17.649a36.5 36.5 0 0 0 4.334 5.518c3.249 3.602 2.947 5.923 2.947 5.923a3.23 3.23 0 0 1-2.42 3.517a2.385 2.385 0 0 1-2.669-.832l-.991-1.61s-.724 4.21 1.78 5.647");
}

.jascrv2te {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.869C12.005 9.79 4.88 21.569 4.522 24.279s3.79 13.279 3.79 13.279A30.12 30.12 0 0 1 24 23.227m0 0s12.264-6.324 14.946-6.677");
}

.js6p-gbdc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.982 42.131A10 10 0 0 0 24 41.617");
}

.u8yx54bbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.869c11.995 3.921 19.12 15.7 19.478 18.41a8.7 8.7 0 0 1-.303 2.634c-.172.766-.4 1.616-.66 2.492c-.225.766-.474 1.55-.727 2.317c-.323.977-.653 1.923-.953 2.759c-.642 1.79-1.147 3.077-1.147 3.077A30.12 30.12 0 0 0 24 23.227");
}

</style>
