<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb8ed0bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:edit-square" /></template>
<style>
.qb8ed0bdk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 1.75h10.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 17.125V6.875q0-2.123 1.501-3.624T6.875 1.75m10.251 8.305q1.591-1.59 0-3.181t-3.181 0l-4.243 4.241q-.66.66-.66 1.592q0 .063.003.124q-.788.248-1.06 1.062l-.056.168q-.31.931.384 1.626q.695.694 1.626.384l.168-.057q.814-.271 1.062-1.059q.061.003.124.003q.932 0 1.591-.66z");
}

</style>
