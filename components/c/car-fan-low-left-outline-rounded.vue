<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syjv049ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-low-left-outline-rounded" /></template>
<style>
.syjv049ze {
  fill: currentColor;
  d: path("M14.606 21.75q-.177.104-.375.062t-.302-.22l-2.727-3.9H4.881q-.572 0-1.009-.363T3.31 16.4l-1.152-5.74q-.148-.777.355-1.372t1.28-.596q.56 0 1.005.387t.637 1.03l1.623 5.641h3.627q.338 0 .637.166q.3.167.497.488l2.97 4.65q.103.177.048.375t-.231.321M3.48 7.692q-.614 0-1.038-.424T2.02 6.231t.424-1.038t1.038-.424t1.037.424t.424 1.038t-.424 1.037t-1.037.424m13.106 3.311q-.137-.053-.268-.184l-3.215-3.196q-.146-.146-.156-.354q-.01-.207.156-.353q.146-.147.347-.147t.347.147l2.587 2.528V3.5q0-.213.143-.357q.143-.143.357-.143q.213 0 .356.143t.144.357v5.944l2.586-2.529q.146-.146.347-.146t.347.146t.146.344t-.146.345l-3.215 3.215q-.13.131-.267.184t-.299.053t-.298-.053");
}

</style>
