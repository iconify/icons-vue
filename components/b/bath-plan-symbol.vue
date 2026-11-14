<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id2n3sb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bath-plan-symbol" /></template>
<style>
.id2n3sb2o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 4.75h10.25q2.123 0 3.624 1.501t1.501 3.624v4.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 14.125v-4.25q0-2.123 1.501-3.624T6.875 4.75M15 7.5H9q-1.864 0-3.182 1.318T4.5 12t1.318 3.182T9 16.5h6q1.864 0 3.182-1.318T19.5 12t-1.318-3.182T15 7.5");
}

</style>
