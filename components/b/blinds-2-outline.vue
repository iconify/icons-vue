<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmmcuacgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blinds-2-outline" /></template>
<style>
.wmmcuacgp {
  fill: currentColor;
  d: path("M4.98 21V7.77H3V5.384q0-.994.696-1.69T5.385 3h13.23q.981 0 1.683.702T21 5.394v2.375h-2V21zm1-1H18v-3.712H5.98zm0-4.711H18v-3.731h-2.788v1.384q0 .213-.144.357t-.356.143q-.195 0-.347-.143q-.153-.144-.153-.357v-1.384H5.98zm0-4.731h8.232V7.769H5.98zm9.232 0H18V7.769h-2.788zM4 6.769h16V5.391q0-.585-.398-.988T18.616 4H5.385q-.589 0-.987.398T4 5.385zm16 0H4z");
}

</style>
