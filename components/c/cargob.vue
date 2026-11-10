<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="bvbi-0bug"/><path class="h9nzlm7ir"/><path class="zpt03tbyi"/><circle class="glbmhw76i"/><circle class="zkylo39gr"/><path class="u013du7pf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cargob" /></template>
<style>
.bvbi-0bug {
  d: path("M24 8.182c-.697-.001-1.375.236-2.522.708L7.395 14.692C4.755 15.779 4.5 15.767 4.5 18.885V30.09c0 1.97.64 2.215 2.79 3.11l14.532 6.05c.932.389 1.54.577 2.178.569c.637.008 1.246-.18 2.179-.569l14.53-6.05c2.152-.895 2.791-1.14 2.791-3.11V18.885c0-3.118-.255-3.106-2.895-4.193L26.522 8.89c-1.147-.472-1.825-.71-2.522-.708");
}

.glbmhw76i {
  cx: 12.535px;
  cy: 27.989px;
  r: 3.75px;
}

.h9nzlm7ir {
  d: path("m15.295 14.461l8.7 2.574l-.685-2.085l3.78.912l-.815-1.824l6.484.684l-8.83-2.737l.88 1.988l-4.138-.978l1.108 1.923zm21.181 14.064l-2.222-4.29l-2.528 4.213l-13.33.307l-5.746-.716l3.065-4.034m-1.073-2.375l3.575 6.895");
}

.u013du7pf {
  d: path("m21.15 21.592l13.008 2.633");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zkylo39gr {
  cx: 36.552px;
  cy: 28.295px;
  r: 2.58px;
}

.zpt03tbyi {
  d: path("m18.779 18.183l2.375.23l-.843.995l2.528 9.04m-9.372-6.716l2.631-.332");
}

</style>
