<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvw_ftbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:farm-gateway" /></template>
<style>
.qvw_ftbxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21V10q0-.184.009-.368t.027-.367t.045-.365t.063-.363t.081-.359t.098-.355t.115-.35t.133-.343q.07-.17.149-.337q.079-.166.166-.328q.086-.163.181-.321t.197-.311t.212-.301t.226-.29q.117-.142.241-.279q.124-.136.254-.266t.266-.254q.137-.124.279-.241t.29-.226t.301-.212q.153-.102.311-.197t.321-.181t.328-.166q.167-.079.337-.149q.17-.071.343-.133t.35-.115t.355-.098t.359-.081t.363-.063t.365-.045t.367-.027t.368-.009t.368.009t.367.027t.365.045t.363.063t.359.081t.355.098t.35.115t.343.133q.17.07.337.149q.166.079.328.166q.163.086.321.181t.311.197t.301.212t.29.226q.142.117.279.241q.136.124.266.254t.254.266q.124.137.241.279t.226.29t.212.301t.197.311t.181.321t.166.328q.079.167.149.337q.071.17.133.343t.115.35t.098.355t.081.359t.063.363t.045.365t.027.367T18 10v2.19M3 12h15m-7.5 0v9m7.5-.5h.01m-1.778-2.107a2.75 2.75 0 0 1 3.536 0m-5.303-2.106a5.5 5.5 0 0 1 7.07 0");
}

</style>
