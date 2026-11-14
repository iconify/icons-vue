<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z-5ox7box"/><path class="end92ks8s"/><path class="hhig4sbno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:children-book" /></template>
<style>
.end92ks8s {
  d: path("M21.5 12.515V3H16q-.197 0-.392.019q-.196.02-.388.058q-.193.038-.381.095t-.37.132q-.181.076-.355.168q-.173.093-.336.202t-.316.234q-.151.125-.29.264t-.264.29q-.125.152-.234.316q-.109.163-.202.336q-.092.174-.168.355q-.075.182-.132.37t-.095.381t-.058.388T12 7v12.377");
}

.hhig4sbno {
  d: path("M16 15.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z-5ox7box {
  d: path("M11.692 20.177q-.092-.188-.209-.361q-.118-.173-.258-.328t-.301-.29t-.338-.245q-.178-.11-.369-.195t-.392-.142q-.201-.058-.409-.087T9 18.5H2.5V3H8q.197 0 .392.019q.196.02.388.058q.193.038.381.095t.37.132q.181.076.355.168q.173.093.336.202t.316.234q.151.125.29.264t.264.29q.125.152.234.316q.109.163.202.336q.092.174.168.355q.075.182.132.37t.095.381t.058.388T12 7v12.377");
}

</style>
