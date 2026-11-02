<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnejyvb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:golf-fill-sharp" /></template>
<style>
.hnejyvb-w {
  fill: currentColor;
  d: path("m10.447 2.106l8 4a.998.998 0 0 1 0 1.788L11 11.618V17a1 1 0 0 1-2 0V3a1 1 0 0 1 1.447-.894M7 19c0 .048.049.099.078.133c.335.396 1.086.629 1.572.731c1.139.241 2.674.184 3.731-.344c.197-.099.397-.217.541-.387c.029-.034.078-.085.078-.133a1 1 0 0 1 2 0c0 .53-.211 1.023-.551 1.424c-1.78 2.103-7.118 2.103-8.898 0C5.211 20.023 5 19.53 5 19a1 1 0 0 1 2 0");
}

</style>
