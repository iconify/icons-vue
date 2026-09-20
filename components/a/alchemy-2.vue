<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k94-12bgl"/><path class="miy9g3hyl"/><circle class="uo_pzxb9r"/><path class="uxnr15zpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alchemy-2" /></template>
<style>
.k94-12bgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.976 43.5c-5.15 0-4.342-5.566-3.433-8.223l9.31-27.212c-1.946-.878-2.17-3.703.111-3.56h12.072c2.28-.143 2.057 2.682.11 3.56l9.31 27.212c.91 2.657 1.718 8.223-3.432 8.223z");
}

.miy9g3hyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.838 22.766a2.874 2.874 0 1 1-5.748 0a2.874 2.874 0 1 1 5.748 0m-3.264-10.92a2.194 2.194 0 1 1-.553 4.315q.007.085.006.173a2.874 2.874 0 1 1-1.627-2.588a2.19 2.19 0 0 1 2.174-1.9m-5.982 8.798a2.477 2.477 0 1 1-4.954.001a2.477 2.477 0 0 1 4.954 0");
}

.uo_pzxb9r {
  cx: 32.557px;
  cy: 24.624px;
  r: 1.327px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uxnr15zpr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.004 9.787a1.327 1.327 0 1 1-2.654 0a1.327 1.327 0 0 1 2.653 0zM22.852 25.5a1.327 1.327 0 1 1-1.328-1.328h.001c.733 0 1.327.594 1.327 1.327zm14.014 2.209H11.132");
}

</style>
