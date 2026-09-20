<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc8_bmbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-mid-left-rounded" /></template>
<style>
.pc8_bmbsl {
  fill: currentColor;
  d: path("M14.606 21.75q-.177.104-.375.062t-.302-.22l-2.727-3.9H4.881q-.572 0-1.009-.363T3.31 16.4l-1.152-5.74q-.148-.777.355-1.372t1.28-.596q.56 0 1.005.387t.637 1.03l1.623 5.641h3.627q.338 0 .637.166q.3.167.497.488l2.97 4.65q.103.177.048.375t-.231.321M3.48 7.692q-.614 0-1.038-.424T2.02 6.231t.424-1.038t1.038-.424t1.037.424t.424 1.038t-.424 1.037t-1.037.424m12.896 3.204l-3.196-3.215q-.131-.131-.184-.267q-.053-.137-.053-.298q0-.162.053-.299t.184-.267l3.215-3.215q.146-.146.345-.137q.198.01.344.156t.146.337t-.147.338l-2.528 2.587H20.5q.214 0 .357.143t.143.357t-.143.356t-.357.144h-5.944l2.529 2.586q.14.146.143.347t-.144.347q-.145.166-.353.166t-.354-.166");
}

</style>
