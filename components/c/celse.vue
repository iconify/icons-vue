<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bj9vgjlzj"/><path class="lee-tab5i"/><path class="mtaf8bc5w"/><circle class="v8j4b65xi"/><path class="wsfa7_9uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:celse" /></template>
<style>
.bj9vgjlzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.485 23.236A21.499 21.499 0 1 1 9.582 8.052a21.5 21.5 0 0 1 26.6-1.769M16.13 35.728H5.983m25.887 0h10.146");
}

.lee-tab5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.416 45.304l-.06-11.348l.952-1.232l.659-9.48l-11.725.584l4.886 11.9c0 1.35-2.694 4.978-5.323 5.243m15.777 4.333l.06-11.347l-.952-1.233l-.659-9.48l11.724.584l-4.886 11.9c0 1.35 2.698 4.98 5.328 5.244");
}

.mtaf8bc5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.77 33.61l4.335-9.782l.105-2.346l13.564-1.084v-1.59m20.454 14.808l-4.336-9.787l-.106-2.347l-13.564-1.084v-1.59");
}

.v8j4b65xi {
  cx: 24px;
  cy: 16.968px;
  r: 2.208px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wsfa7_9uo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.041 13.587a4.29 4.29 0 0 1 5.92.003m-7.247-2.045a6.207 6.207 0 0 1 8.574 0");
}

</style>
