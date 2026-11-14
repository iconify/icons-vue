<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkvixch-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hair-oil" /></template>
<style>
.vkvixch-e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 6.326V4.5q0-2.75 2.75-2.75t2.75 2.75v1.826q1.5.337 1.5 2.174q0 .79-.277 1.303q.686.358 1.276.948q.888.888 1.25 1.993q-2.749 3.232-2.749 6.006q0 1.466.772 2.612q-1.264.888-2.897.888h-3.25q-2.123 0-3.624-1.501T3.25 17.125v-2.75q0-2.123 1.501-3.624q.59-.59 1.276-.948Q5.75 9.29 5.75 8.5q0-1.837 1.5-2.174m1.5-.076V4.5q0-1.25 1.25-1.25t1.25 1.25v1.75zm10.303 6.743Q22 16.208 22 18.75q0 3.5-3.5 3.5t-3.5-3.5q0-2.542 2.947-5.757q.05-.054.11-.098q.059-.044.126-.075t.139-.049q.072-.017.145-.02q.074-.004.147.008q.073.011.143.036q.069.026.132.064t.118.088q.024.022.046.046M16.5 18.75q0-1.733 2-4.114q2 2.381 2 4.114q0 2-2 2t-2-2");
}

</style>
