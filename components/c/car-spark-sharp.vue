<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhmil1blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-spark-sharp" /></template>
<style>
.bhmil1blk {
  fill: currentColor;
  d: path("M17.98 10.116q-.15 0-.2-.15q-.36-1.391-1.358-2.388q-.997-.997-2.387-1.359q-.15-.05-.15-.2q0-.175.15-.2q1.39-.361 2.387-1.358t1.359-2.388q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.387 1.358q-.998.997-1.36 2.388q-.024.15-.2.15m-1.398 5.576q.466 0 .788-.326q.322-.327.322-.793q0-.467-.326-.79q-.327-.321-.793-.321q-.467 0-.79.326q-.321.327-.321.794q0 .466.326.788q.327.322.794.322m-9.154 0q.466 0 .788-.326q.323-.327.323-.793q0-.467-.327-.79q-.327-.321-.793-.321q-.467 0-.79.326q-.321.327-.321.794q0 .466.326.788q.327.322.793.322M4 20v-7.846L6.162 6h5.344q-.012.25.004.5t.069.5h-4.69l-1.473 4.154h8.678q.829.662 1.827 1.004t2.053.342q.528-.012 1.029-.09q.5-.077.997-.237V20h-1.23v-2H5.23v2z");
}

</style>
