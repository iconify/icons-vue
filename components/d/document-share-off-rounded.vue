<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5m60n67s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:document-share-off-rounded" /></template>
<style>
.s5m60n67s {
  fill: currentColor;
  d: path("m19.8 21.33l-3.715-3.714q-.44.325-.985.288t-.948-.44t-.44-.948t.288-.985l-2.084-2.085q-.449.721-.682 1.557T11 16.737q0 .896.233 1.73q.232.835.667 1.589q.192.317.024.63t-.516.314H6.616q-.691 0-1.153-.462T5 19.385V6.53l-2.6-2.6q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16l17.4 17.4q.14.14.15.344t-.15.364t-.354.16t-.354-.16m-5.533-10.312L6.325 3.052q.066-.029.137-.04Q6.532 3 6.616 3H14.5L19 7.5v1.896q0 .298-.242.497t-.54.163q-.57-.048-1.13.01t-1.054.207q-.48.13-.911.32t-.856.426m4.167 4.034Q18 14.619 18 13.987t.434-1.067t1.066-.433t1.066.433t.434 1.067t-.434 1.066q-.433.434-1.066.434t-1.066-.434M14 4v4h4z");
}

</style>
