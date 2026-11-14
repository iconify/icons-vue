<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghrhf2bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-clubs-crossed" /></template>
<style>
.ghrhf2bsj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.938 13.167l2.59 3.454q2.058-.591 4.099.037q2.623.807 2.623 2.842q0 2.75-4.75 2.75H16q-1.182 0-1.652-1.033q-.346-.762-.085-1.623l.209-1.882L12 14.417l-2.472 3.295l.209 1.882q.261.861-.085 1.623Q9.182 22.25 8 22.25H6.5q-4.75 0-4.75-2.75q0-2.035 2.623-2.842q2.041-.628 4.099-.037l2.59-3.454L3.4 2.95q-.09-.119-.127-.264q-.037-.144-.015-.292t.097-.276t.195-.218t.264-.127t.292-.015q.148.021.276.097t.218.195l7.4 9.867l7.4-9.867q.044-.059.099-.108q.055-.05.119-.087q.063-.038.133-.063q.07-.024.143-.034t.147-.007t.145.022t.138.051t.126.076q.119.09.195.218t.097.276t-.015.292q-.037.145-.127.264z");
}

</style>
