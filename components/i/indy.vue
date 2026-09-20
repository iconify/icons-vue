<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="l_i4kssfy"/><circle class="gh7yyej2x"/><path class="n3p9gqofk"/><path class="y3zeu0bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:indy" /></template>
<style>
.gh7yyej2x {
  cx: 14.633px;
  cy: 17.657px;
  r: 0.75px;
  fill: currentColor;
}

.l_i4kssfy {
  width: 38.349px;
  height: 38.349px;
  x: 4.826px;
  y: 4.826px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.146px;
  ry: 4.146px;
}

.n3p9gqofk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.889 20.704l-1.607 6.592m7.525 0l1-4.104c.336-1.374-.507-2.488-1.88-2.488c-1.375 0-2.76 1.114-3.095 2.488m-1 4.104l1.607-6.592m11.645 2.488c.334-1.374-.508-2.488-1.881-2.488c-1.375 0-2.76 1.114-3.094 2.488l-.394 1.617c-.336 1.373.507 2.487 1.88 2.487c1.374 0 2.759-1.114 3.095-2.487m-.608 2.487l2.427-9.95m6.457 3.358l-1 4.104c-.336 1.374-1.72 2.488-3.095 2.488c-1.373 0-2.216-1.114-1.88-2.488l1-4.104");
}

.y3zeu0bud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.966 24.808l-.82 3.358c-.334 1.374-1.72 2.488-3.093 2.488c-.687 0-1.242-.279-1.582-.729");
}

</style>
