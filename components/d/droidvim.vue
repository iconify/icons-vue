<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ro3rxgb0v"/><path class="vyet1y67i"/><path class="ywfni3b7n"/><path class="cymxiyole"/><path class="yth42ccxw"/><circle class="qtlohj0es"/><path class="w3ynj1b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:droidvim" /></template>
<style>
.cymxiyole {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 0 2;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.6 37.5h14");
}

.qtlohj0es {
  cx: 22.5px;
  cy: 16px;
  r: 0.8px;
  fill: currentColor;
}

.ro3rxgb0v {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 5.8;
  d: path("M12.4 6.9c.6-3.3 22.1-3.2 23.2 0v34.4c-1.7 2.9-21.9 3-23.2 0Zm0 1.3h23.2m0 31.4H12.4");
}

.vyet1y67i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.3 6.5h3.6");
}

.w3ynj1b7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.5 18.4v5.3");
}

.yth42ccxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.4 15.7l-2.7 8l-2.6-8m9.6 4.8a2 2 0 0 1 2-2a2 2 0 0 1 2 2v3.2m-4-5.2v5.2m4-3.2a2 2 0 0 1 2-2a2 2 0 0 1 2 2v3.2");
}

.ywfni3b7n {
  fill: none;
  stroke: currentColor;
  d: path("M12.5 35.4h22.7");
}

</style>
