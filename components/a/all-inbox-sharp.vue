<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_kblgblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:all-inbox-sharp" /></template>
<style>
.o_kblgblg {
  fill: currentColor;
  d: path("M13.5 13.616q.908 0 1.579-.569q.671-.568.671-1.431h3.75V4h-12v7.616h3.75q0 .863.674 1.431t1.576.569M6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
