<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmpfnrx3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:document-share-off" /></template>
<style>
.bmpfnrx3i {
  fill: currentColor;
  d: path("m20.154 21.685l-4.07-4.07q-.44.326-.984.289t-.948-.44t-.44-.948q-.037-.545.288-.985l-2.084-2.085q-.449.721-.682 1.557T11 16.737q0 1.194.406 2.277T12.562 21H6.616q-.691 0-1.153-.462T5 19.385V6.53L2.046 3.577l.708-.708L20.86 20.977zm-5.887-10.666L6.325 3.052q.066-.029.137-.04Q6.532 3 6.616 3H14.5L19 7.5v2.685q-.244-.074-.494-.088T18 10.064q-1.023-.039-1.972.209t-1.76.746m4.166 4.034Q18 14.619 18 13.987t.434-1.067t1.066-.433t1.066.433t.434 1.067t-.434 1.066q-.433.434-1.066.434t-1.066-.434M14 4v4h4z");
}

</style>
