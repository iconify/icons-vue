<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dosm3ot4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:grocery-bag-full" /></template>
<style>
.dosm3ot4q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.62 3.622q-.583-2.173-2.755-1.59q-.9.241-1.366 1.048t-.225 1.707l1.165 4.346q.031.118.072.228q-2.261.501-2.261 3.264v5.75q0 3.375 3.375 3.375h8.75q3.375 0 3.375-3.375v-5.75q0-2.812-2.343-3.281q2.439-1.83 1.833-5.467q-.005-.03-.012-.059q-.018-.072-.05-.138q-.031-.067-.075-.126q-.044-.06-.099-.109q-.055-.05-.118-.088t-.133-.063t-.143-.036t-.146-.007q-.074.003-.146.021q-4.71 1.178-5.043 5.978h-2.52q.209-.615.03-1.281zm5.19 5.367q3.109-1.091 3.036-3.998q-2.664 1.035-3.036 3.998");
}

</style>
