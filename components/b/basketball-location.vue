<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ih7kngbza"/><path class="t27oicnse"/><path class="ivzpdhhtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basketball-location" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ih7kngbza {
  d: path("M11.769 20.72q-.376.388-.769.78C6.5 17 3.5 13 3.5 9.5q0-.184.009-.368t.027-.367t.045-.365t.063-.363t.081-.359t.098-.355t.115-.35t.133-.343t.149-.337q.079-.166.166-.328q.086-.163.181-.321t.197-.311t.212-.301t.226-.29t.241-.279t.254-.266t.266-.254t.279-.241t.29-.226t.301-.212t.311-.197t.321-.181q.162-.087.328-.166q.167-.079.337-.149q.17-.071.343-.133t.35-.115t.355-.098t.359-.081t.363-.063t.365-.045t.367-.027T11 2t.368.009t.367.027t.365.045t.363.063t.359.081t.355.098t.35.115t.343.133t.337.149t.328.166q.163.086.321.181t.311.197t.301.212t.29.226q.142.117.279.241q.136.124.266.254t.254.266t.241.279q.116.142.226.29t.212.301t.197.311t.181.321q.087.162.166.328q.079.167.149.337q.071.17.133.343t.115.35t.098.355t.081.359t.063.363t.045.365t.027.367t.009.368a7 7 0 0 1-.22 1.703");
}

.ivzpdhhtj {
  d: path("M15.25 15.25q2.75 2.75 0 5.5m5.5-5.5q-2.75 2.75 0 5.5");
}

.t27oicnse {
  d: path("M8.25 9.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0m0 0h8");
}

</style>
