<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_9kswldw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-mid-right-outline-rounded" /></template>
<style>
.a_9kswldw {
  fill: currentColor;
  d: path("M9.37 21.75q-.178-.104-.22-.312t.061-.384l2.97-4.65q.198-.321.497-.488t.637-.166h3.627l1.623-5.64q.193-.644.637-1.031t1.006-.387q.776 0 1.28.596t.354 1.372l-1.151 5.74q-.125.566-.563.929t-1.009.363h-6.321l-2.727 3.92q-.104.177-.314.21q-.21.032-.388-.072M20.52 7.692q-.613 0-1.037-.424t-.424-1.037t.424-1.038t1.037-.424t1.038.424t.424 1.038t-.424 1.037t-1.038.424M6.916 10.896q-.147-.146-.147-.347t.147-.347l2.528-2.586H3.5q-.213 0-.357-.144Q3 7.329 3 7.116q0-.214.143-.357t.357-.143h5.944L6.916 4.029q-.147-.146-.137-.347t.156-.347t.344-.146t.344.146l3.196 3.215q.131.13.184.267t.053.299t-.053.298t-.184.267l-3.196 3.215q-.146.146-.354.156q-.207.01-.353-.156");
}

</style>
