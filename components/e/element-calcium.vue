<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l66x5wb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:element-calcium" /></template>
<style>
.l66x5wb9m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.625 2.25h-9.25q-2.123 0-3.624 1.501T2.25 7.375v9.25q0 2.123 1.501 3.624t3.624 1.501h9.25q2.123 0 3.624-1.501t1.501-3.624v-9.25q0-2.123-1.501-3.624T16.625 2.25M4.885 9.381q.68-2.606 3.3-1.98q2.132.51 2.15 2.349h3.33q.018-1.839 2.15-2.349q2.62-.626 3.3 1.98q.448 1.715-.52 2.619q.968.904.52 2.619q-.68 2.606-3.3 1.98q-2.132-.51-2.15-2.349h-3.33q-.018 1.839-2.15 2.349q-2.62.626-3.3-1.98q-.448-1.715.521-2.619q-.969-.904-.521-2.619");
}

</style>
