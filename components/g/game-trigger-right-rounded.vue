<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bva5me_ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-trigger-right-rounded" /></template>
<style>
.bva5me_ab {
  fill: currentColor;
  d: path("M7.882 15.028q.132-.126.132-.3v-2.047h1.175l1.432 2.275q.06.09.14.144t.193.054q.246 0 .376-.218t-.024-.428l-1.294-2.04q.623-.218.937-.645t.315-1.054q0-.938-.561-1.382q-.56-.445-1.724-.445H7.966q-.344 0-.576.233q-.232.232-.232.575v4.979q0 .173.116.299q.117.126.297.126t.311-.126m.137-3.103L8 9.758h.933q.707 0 1.072.277q.364.278.364.784q0 .531-.357.819t-1.008.287zm7.171 3.103q.127-.126.127-.3V9.77h1.52q.182 0 .297-.115q.116-.115.116-.296t-.116-.298t-.297-.118h-3.908q-.182 0-.298.115t-.115.297q0 .18.115.298q.116.117.298.117h1.533v4.96q0 .173.126.299t.3.126t.302-.126M3 17.384V8.27q0-1.356.977-2.322t2.35-.966h11.346q1.373 0 2.35.966T21 8.269v9.116q0 .666-.474 1.14T19.385 19H4.615q-.666 0-1.14-.475T3 17.386");
}

</style>
