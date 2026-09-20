<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v190iccfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-highlighter-off-rounded" /></template>
<style>
.v190iccfn {
  fill: currentColor;
  d: path("m18.223 4.716l1.754 1.753q.485.485.485 1.131t-.485 1.13l-3.646 3.653q-.223.223-.552.223t-.552-.223L12.31 9.466q-.223-.224-.223-.552q0-.33.223-.552l3.652-3.646q.484-.485 1.13-.485q.647 0 1.131.485m1.898 16.101q-.165.166-.356.166q-.192 0-.357-.166l-5.762-5.755l-4.223 4.229q-.484.484-1.133.484t-1.134-.484l-.192-.193l-.683.677q-.217.206-.514.33q-.296.126-.607.126H4.014q-.273 0-.373-.252t.094-.444l1.838-1.833l-.154-.154q-.484-.484-.49-1.14q-.006-.654.479-1.139l4.223-4.223l-6.454-6.454q-.146-.146-.156-.347t.156-.366t.357-.166t.357.166l16.23 16.23q.146.147.156.345t-.156.363");
}

</style>
