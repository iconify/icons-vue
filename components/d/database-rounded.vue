<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peimyccma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:database-rounded" /></template>
<style>
.peimyccma {
  fill: currentColor;
  d: path("M17.692 9.998q2.327-1.021 2.327-2.479t-2.327-2.478t-5.673-1.022t-5.682 1.022Q4 6.06 4 7.519t2.337 2.479t5.682 1.021t5.673-1.021m-3.216 2.367q1.259-.194 2.366-.573t1.95-.939t1.227-1.295v2.961q-.384.735-1.227 1.295q-.842.561-1.95.94q-1.107.379-2.366.572T12 15.519t-2.476-.193t-2.357-.572t-1.94-.94T4 12.52V9.558q.384.734 1.227 1.295q.842.56 1.94.94q1.098.378 2.357.572t2.476.193t2.476-.193m0 4.5q1.258-.194 2.366-.573t1.95-.939t1.227-1.295V17q-.384.735-1.227 1.295q-.842.56-1.95.94q-1.107.379-2.366.572T12 20t-2.476-.193t-2.357-.572t-1.94-.94T4 17v-2.942q.385.734 1.227 1.295t1.94.94t2.357.572t2.476.193t2.476-.194");
}

</style>
