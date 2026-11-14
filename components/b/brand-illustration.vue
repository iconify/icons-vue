<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a50t2kbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:brand-illustration" /></template>
<style>
.a50t2kbrw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.75h10.25q2.123 0 3.624 1.501t1.501 3.624v8.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 16.125v-8.25q0-2.123 1.501-3.624T6.875 2.75M9.25 6.5q-3.75 0-3.75 3.75T9.25 14q.176 0 .344-.008l-.51.8v.001q-.714 1.123-.073 2.29t1.972 1.167h5.034q1.331 0 1.972-1.167t-.073-2.291l-2.518-3.956q-.664-1.041-1.898-1.041q-.269 0-.512.05Q12.792 6.5 9.25 6.5");
}

</style>
