<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_8l3obda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:digital-compendium" /></template>
<style>
.h_8l3obda {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.875 1.75h6.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-6.25q-2.123 0-3.624-1.501T3.75 17.125V6.875q0-2.123 1.501-3.624T8.875 1.75m2.888 6.38l-2.052-.684q-1.093-.363-2.027.31T6.75 9.581v4.838q0 1.622 1.539 2.135l3 1q.156.051.311.081q.183.115.4.115t.4-.115q.156-.03.311-.081l3-1q1.539-.513 1.539-2.135V9.581q0-1.152-.934-1.825t-2.027-.31l-2.052.684q-.237.079-.474 0");
}

</style>
