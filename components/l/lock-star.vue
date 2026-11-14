<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh0znobxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lock-star" /></template>
<style>
.bh0znobxz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 9.499q1.109.362 1.999 1.252q1.501 1.501 1.501 3.624v2.25q0 2.123-1.501 3.624t-3.624 1.501h-6.25q-2.123 0-3.624-1.501T3.75 16.625v-2.25q0-2.123 1.501-3.624q.89-.89 1.999-1.252V7q0-1.968 1.391-3.359T12 2.25t3.359 1.391T16.75 7zm-8-.248l.125-.001h6.25l.125.001V7q0-3.25-3.25-3.25T8.75 7zm4.363 3.809q-.342-.691-1.113-.691t-1.113.691l-.093.187q-.174.354-.565.411l-.205.03q-.762.112-1 .844q-.239.732.313 1.273l.148.145q.283.275.216.664l-.035.204q-.13.76.493 1.214t1.309.095l.183-.096q.349-.184.697-.001l.186.099q.684.357 1.307-.097t.493-1.214l-.035-.204q-.067-.389.215-.664l.151-.147q.55-.539.311-1.271q-.238-.732-1-.844l-.206-.03q-.39-.057-.565-.412z");
}

</style>
