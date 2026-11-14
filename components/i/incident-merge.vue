<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qzgrfjbcn"/><path class="uz-oo6b5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:incident-merge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qzgrfjbcn {
  d: path("M14.532 17.5h-6.95q-.173 0-.344-.023q-.171-.022-.338-.067q-.166-.045-.326-.111q-.159-.066-.309-.153q-.149-.086-.286-.192q-.137-.105-.258-.227q-.122-.123-.227-.26q-.104-.137-.19-.287t-.152-.31q-.065-.159-.109-.326t-.066-.338t-.021-.344t.025-.344t.069-.337t.113-.326q.067-.159.154-.308l3.918-6.684q.043-.074.091-.144q.048-.071.1-.139q.053-.067.109-.131q.057-.064.118-.124t.125-.116t.132-.108t.139-.099t.146-.09q.074-.042.15-.08q.077-.037.156-.07q.079-.032.16-.06t.164-.049t.166-.038t.168-.028t.17-.017q.086-.005.171-.005t.171.005q.085.006.17.017q.084.011.168.028q.084.016.166.038q.083.022.164.049t.16.06t.156.07t.15.08t.146.09q.071.047.139.099t.132.108t.125.116t.118.124q.056.064.109.131q.052.068.1.139q.048.07.091.144l2.882 4.917M11.5 8.5V12m0 2.5h.01");
}

.uz-oo6b5p {
  d: path("m15 14l3 3l3-3m-3 3v4.5m-1.75-1.75L18 21.5l1.75-1.75");
}

</style>
