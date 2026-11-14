<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frzvfxb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-food-jar" /></template>
<style>
.frzvfxb2h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 2.25H6.75q-2.5 0-2.5 2.5v1q0 1.036.732 1.768q.35.349.768.532v.51q-2 1.243-2 3.94v6q0 1.346.952 2.298T7 21.75h10q1.346 0 2.298-.952t.952-2.298v-6q0-2.697-2-3.94v-.51q.418-.183.768-.532q.732-.732.732-1.768v-1q0-2.5-2.5-2.5m1.5 14.5H5.25v-3h13.5zm-13.5 1.5h13.5v.25q0 .725-.513 1.237q-.512.513-1.237.513H7q-.725 0-1.237-.513q-.513-.512-.513-1.237zm.006-6q.093-1.836 1.579-2.579q.094-.047.171-.117t.132-.16t.083-.189Q7.25 9.104 7.25 9v-.75h9.5V9q0 .104.029.205q.028.1.083.189t.132.16t.171.117q1.486.743 1.579 2.579z");
}

</style>
