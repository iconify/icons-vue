<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yy0ssrc3s"/><circle transform="rotate(-89.932 33.548 23.196)" class="tgam5tbem"/><path class="x1_ckxx4y"/><circle class="qgnx9yn_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:agc-toolkit" /></template>
<style>
.qgnx9yn_y {
  cx: 13.642px;
  cy: 29.259px;
  r: 2.724px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tgam5tbem {
  cx: 33.548px;
  cy: 23.196px;
  r: 7.501px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x1_ckxx4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.62 30.175q.06-.456.064-.916a8 8 0 0 0-.064-.916l1.984-1.554a.46.46 0 0 0 .114-.6l-1.878-3.258a.46.46 0 0 0-.573-.201l-2.341.944a7.2 7.2 0 0 0-1.585-.917l-.353-2.488a.46.46 0 0 0-.459-.394h-3.766a.46.46 0 0 0-.458.394l-.353 2.488a7 7 0 0 0-1.585.917l-2.35-.944a.46.46 0 0 0-.573.201L4.565 26.19c-.12.2-.07.459.115.6l1.98 1.553q-.06.456-.065.917q.004.46.064.916l-1.98 1.553a.46.46 0 0 0-.114.6l1.879 3.258a.46.46 0 0 0 .573.202l2.34-.944a7.2 7.2 0 0 0 1.586.916l.353 2.488a.46.46 0 0 0 .458.394h3.757a.46.46 0 0 0 .458-.394l.353-2.488a7 7 0 0 0 1.585-.916l2.342.944c.214.087.46 0 .572-.202L22.7 32.33c.12-.2.07-.459-.115-.6z");
}

.yy0ssrc3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.2 33.436h17.935c1.864 0 3.365-1.5 3.365-3.365v-13.81c0-1.864-1.5-3.365-3.365-3.365h-1.67l-1.657-3.538h-7.436l-1.66 3.538h-14.98a3.357 3.357 0 0 0-3.365 3.365v7.228");
}

</style>
