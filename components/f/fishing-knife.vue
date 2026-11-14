<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcisgib2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fishing-knife" /></template>
<style>
.hcisgib2c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.027 2.918l-13.25 10.75q-.03.024-.057.052q-.106.105-.163.243t-.057.287q0 .057.009.114q-.58.171-1.039.631L2.995 17.47q-.733.732-.733 1.768q0 1.035.733 1.767q.732.733 1.767.733q1.036 0 1.768-.733l2.475-2.475q.46-.459.631-1.039q.13.02.259-.005q.128-.025.241-.093q9.016-5.41 11.092-13.711q.021-.085.022-.172t-.018-.172t-.057-.164t-.093-.147q-.046-.057-.103-.104t-.122-.082q-.065-.036-.135-.057t-.144-.03t-.147-.001q-.074.007-.145.028t-.136.056q-.065.034-.123.081");
}

</style>
