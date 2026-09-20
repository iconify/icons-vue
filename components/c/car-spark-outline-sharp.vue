<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yznl2r02u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-spark-outline-sharp" /></template>
<style>
.yznl2r02u {
  fill: currentColor;
  d: path("M5 17v-4.846v.346v-.077zm2.428-1.308q.466 0 .788-.326q.323-.327.323-.793q0-.467-.327-.79q-.327-.321-.793-.321q-.467 0-.79.326q-.321.327-.321.793q0 .467.326.79q.327.321.793.321m9.155 0q.466 0 .788-.326q.322-.327.322-.793q0-.467-.326-.79q-.327-.321-.793-.321q-.467 0-.79.326q-.321.327-.321.794q0 .466.326.788q.327.322.794.322M4 20v-7.846L6.162 6h5.344q-.012.25.004.5t.069.5h-4.69l-1.473 4.154h8.678q.444.373.971.638q.527.266 1.108.362H5V17h14v-4.602q.256-.05.502-.096t.498-.129V20h-1.23v-2H5.23v2zm13.98-9.885q-.15 0-.2-.15q-.36-1.39-1.358-2.387q-.997-.997-2.387-1.359q-.15-.05-.15-.2q0-.169.15-.2q1.39-.356 2.387-1.356t1.359-2.39q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.387 1.358q-.998.997-1.36 2.387q-.024.15-.2.15");
}

</style>
