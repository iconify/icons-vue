<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew79_ixff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:car-app" /></template>
<style>
.ew79_ixff {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.125 1.75h-4.25q-2.123 0-3.624 1.501T4.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h4.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T14.125 1.75M7.5 12q0-1.864 1.318-3.182T12 7.5t3.182 1.318T16.5 12t-1.318 3.182T12 16.5h-.002q-1.863-.001-3.18-1.318T7.5 12");
}

</style>
