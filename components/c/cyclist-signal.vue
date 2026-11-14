<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxco--bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cyclist-signal" /></template>
<style>
.pxco--bnh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.875 1.75h6.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-6.25q-2.123 0-3.624-1.501T3.75 17.125V6.875q0-2.123 1.501-3.624T8.875 1.75m3.125 3q-2.75 0-2.75 2.75T12 10.25t2.75-2.75T12 4.75m-1.39 9.261l.12-.261h2.54l.12.261q-.89.674-.89 2.239q0 2.75 2.75 2.75T18 16.25t-2.75-2.75q-.227 0-.435.019l-.384-.833q-.045-.098-.116-.179q-.07-.081-.161-.139q-.09-.058-.193-.088t-.211-.03h-3.5q-.107 0-.211.03q-.103.03-.193.088t-.161.139t-.116.179l-.384.833q-.208-.019-.435-.019Q6 13.5 6 16.25T8.75 19t2.75-2.75q0-1.565-.89-2.239");
}

</style>
