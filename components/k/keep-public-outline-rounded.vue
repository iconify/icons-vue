<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_ku5h6om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keep-public-outline-rounded" /></template>
<style>
.m_ku5h6om {
  fill: currentColor;
  d: path("M8.5 15H4.942q-.22 0-.37-.153q-.149-.153-.149-.36v-.28q0-.098.037-.189q.036-.091.11-.164L6 12.423V5h-.5q-.213 0-.356-.144T5 4.499t.144-.356T5.5 4h4.73q.213 0 .357.144t.144.357t-.144.356t-.356.143H7v7.179q0 .332-.13.632t-.349.518L5.85 14h6.996q.213 0 .357.144t.143.357t-.143.356t-.357.143H9.5v4.927q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356zm4.665-4.164Q12 9.67 12 8t1.165-2.835T16 4t2.836 1.165T20 8t-1.164 2.836T16 12t-2.835-1.164m3.898-3.274q.437-.437.437-1.062t-.437-1.062T16 5t-1.062.438T14.5 6.5t.438 1.063T16 8t1.063-.437m.163 3.18q.582-.257 1.007-.745q.105-.123.068-.275q-.038-.154-.18-.235q-.493-.244-1.025-.366Q16.563 9 16.004 9t-1.092.122t-1.033.367q-.143.074-.18.226t.068.283q.425.489 1.006.745t1.226.257t1.227-.257");
}

</style>
