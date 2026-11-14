<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1hrzgkrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:guest-checkout" /></template>
<style>
.a1hrzgkrz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.5 8.25q0-1.864 1.318-3.182T8 3.75t3.182 1.318T12.5 8.25t-1.318 3.182T8 12.75t-3.182-1.318T3.5 8.25m16.313 5.5h-3.625q-2.938 0-2.938 2.938v2.625q.001 2.937 2.938 2.937h3.625q2.936-.001 2.937-2.937v-2.625q0-2.937-2.937-2.938M8 14.75q2.323 0 4.051 1.252q-.051.333-.051.686v2.626q.001 1.371.768 2.425q-.129.011-.268.011h-9q-1.75 0-1.75-1.75q0-2.224 1.902-3.77Q5.474 14.75 8 14.75m6.757 1.75q.09-1.25 1.431-1.25h3.625q1.34.001 1.43 1.25zm-.007 2.813V18h6.5v1.313q-.001 1.436-1.437 1.437h-3.625q-1.437 0-1.438-1.437");
}

</style>
