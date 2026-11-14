<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtjzf0brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ar-annotation" /></template>
<style>
.gtjzf0brl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.247 2.353l6.5 3.742q.314.181.549.406q-.225-.013-.42.099L12 11.135L4.124 6.6q-.195-.112-.42-.099q.235-.225.549-.406l6.5-3.742q1.247-.718 2.494 0M11.25 12.434L3.376 7.9q-.197-.113-.298-.316Q3 7.9 3 8.262v7.476q0 1.446 1.253 2.167l6.5 3.742q.311.179.623.269q-.126-.189-.126-.416zM20.624 7.9q.197-.113.298-.316q.078.316.078.678v5.676q-.956-.817-2.25-.817q-1.45 0-2.475 1.026l-2.501 2.5q-1.024 1.025-1.024 2.474v-6.687zM14 19.875v-.754q0-.931.659-1.59l2.5-2.5q.659-.66 1.591-.66t1.592.66l.627.628q.66.659.66 1.591t-.66 1.592l-2.5 2.499q-.659.659-1.59.659h-.754Q14 22 14 19.875m1.5 0q0 .625.625.625h.754q.31 0 .53-.219l2.5-2.501q.22-.219.22-.53t-.22-.531l-.629-.628q-.219-.22-.53-.22t-.531.22l-2.499 2.5q-.22.22-.22.53zm-2.75 0q0 1.104.361 1.846q-.244.125-.487.195q.126-.189.126-.416z");
}

</style>
