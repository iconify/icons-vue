<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="se66zddwp"/><circle class="j3_4z0nsi"/><circle class="y31kldbhd"/><path class="ylzjbvbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adaptive-you-icon-pack" /></template>
<style>
.j3_4z0nsi {
  cx: 15.433px;
  cy: 24px;
  r: 2.52px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.se66zddwp {
  cx: 24px;
  cy: 24px;
  r: 2.52px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y31kldbhd {
  cx: 32.566px;
  cy: 24px;
  r: 2.52px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ylzjbvbax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.608 3.07c1.677.449 2.64 3.173 4.143 4.04c1.504.869 4.344.34 5.571 1.568c1.228 1.227.7 4.067 1.567 5.571c.868 1.504 3.592 2.466 4.041 4.143S43.503 22.264 43.503 24s1.878 3.931 1.428 5.608s-3.173 2.64-4.04 4.143c-.869 1.504-.34 4.344-1.568 5.571c-1.228 1.228-4.067.7-5.571 1.567s-2.466 3.592-4.143 4.041s-3.872-1.428-5.608-1.428s-3.931 1.878-5.608 1.428s-2.64-3.173-4.143-4.04c-1.504-.869-4.344-.34-5.571-1.568c-1.228-1.228-.7-4.067-1.567-5.571c-.868-1.504-3.592-2.466-4.041-4.143S4.498 25.736 4.498 24S2.62 20.069 3.07 18.392s3.173-2.64 4.04-4.143c.869-1.504.34-4.344 1.568-5.571c1.228-1.228 4.067-.7 5.571-1.567c1.504-.868 2.466-3.592 4.143-4.041S22.264 4.498 24 4.498s3.931-1.878 5.608-1.428");
}

</style>
