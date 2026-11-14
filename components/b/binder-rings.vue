<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en7-d8b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:binder-rings" /></template>
<style>
.en7-d8b0n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.125 1.75h-6.25q-2.123 0-3.624 1.501q-.241.241-.444.499H4Q1.75 3.75 1.75 6q0 2.121 2 2.243v1.514q-2 .122-2 2.243t2 2.243v1.514q-2 .122-2 2.243q0 2.25 2.25 2.25h.807q.203.258.444.499q1.501 1.501 3.624 1.501h6.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T15.125 1.75m-11.126 17q-.749-.001-.749-.75q0-.614.502-.725q.02.78.247 1.475M3.752 6.725Q3.25 6.614 3.25 6q0-.749.749-.75q-.227.695-.247 1.475M3.25 12q0-.612.5-.725v1.45q-.5-.113-.5-.725");
}

</style>
