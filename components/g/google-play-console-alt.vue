<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vod1o00zb"/><path class="i_8rt4qqn"/><circle class="z0ro21buo"/><circle class="k9go-bcwh"/><circle class="zb-8g4ooe"/><circle class="nn0nxebzh"/><path class="o0ayqabbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-play-console-alt" /></template>
<style>
.i_8rt4qqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.913 34.241H14.366a1.56 1.56 0 0 1-1.557-1.557V9.874h25.765V26.93M12.809 15.245h25.765");
}

.k9go-bcwh {
  cx: 23.788px;
  cy: 21.559px;
  r: 1.558px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nn0nxebzh {
  cx: 33.14px;
  cy: 19.685px;
  r: 1.558px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o0ayqabbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.038 20.786l-3.41 3.411m-3.739-1.536l1.536 1.536m-6.794 1.519l3.055-3.055");
}

.vod1o00zb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.184 9.873l-8.942-5.162A1.558 1.558 0 0 0 7.906 6.06v35.88a1.558 1.558 0 0 0 2.336 1.349l31.073-17.94a1.558 1.558 0 0 0 0-2.698l-2.74-1.583");
}

.z0ro21buo {
  cx: 18.529px;
  cy: 26.817px;
  r: 1.558px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zb-8g4ooe {
  cx: 27.526px;
  cy: 25.298px;
  r: 1.558px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
