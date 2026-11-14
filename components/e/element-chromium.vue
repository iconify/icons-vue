<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg6dmzx5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:element-chromium" /></template>
<style>
.gg6dmzx5t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h9.25q2.123 0 3.624 1.501t1.501 3.624v9.25q0 2.123-1.501 3.624t-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 16.625v-9.25q0-2.123 1.501-3.624T7.375 2.25M6.48 13.264q-.38 1.096.294 2.041t1.833.945h6.786q1.16 0 1.833-.945q.674-.945.294-2.041l-1.212-3.501q-.524-1.513-2.126-1.513H9.818q-1.602 0-2.126 1.514z");
}

</style>
