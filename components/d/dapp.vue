<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqo8hdc9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dapp" /></template>
<style>
.iqo8hdc9o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 1.75H6.875q-2.123 0-3.624 1.501q-1.29 1.291-1.471 3.041q-.03.102-.03.208q0 .049.006.098q-.006.137-.006.277v10.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-.14-.006-.277q.006-.049.006-.098q0-.106-.03-.208q-.181-1.75-1.471-3.041q-1.501-1.501-3.624-1.501m-6.357 7.482q.732.732.732 1.768t-.732 1.768T9 13.5q-2.5 0-2.5-2.5T9 8.5q1.036 0 1.768.732M12.75 11q0-2.5 2.5-2.5t2.5 2.5q0 1.036-.732 1.768t-1.768.732t-1.768-.732T12.75 11m-1.982 4.482q.732.732.732 1.768t-.732 1.768T9 19.75q-2.5 0-2.5-2.5t2.5-2.5q1.036 0 1.768.732m1.982 1.768q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5");
}

</style>
