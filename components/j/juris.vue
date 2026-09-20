<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s7i17xbdn"/><path class="i6s7xdo_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:juris" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.i6s7xdo_z {
  fill: var(--svg-color--cc051c, #cc051c);
  d: path("M11.357 13.139c-.159-.285-.486-.854-.644-1.139a618 618 0 0 1 1.93-3.425H10.07L8.14 12l1.93 3.426h3.852c1.396-2.49 3.099-5.51 4.505-8L17.14 5.139a5534 5534 0 0 1-4.505 8h-1.287z");
}

.s7i17xbdn {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.713 9.713a2578 2578 0 0 1-4.505 8H8.782L5.574 12l3.218-5.713h5.139L15.218 4H7.505L3 12c1.09 1.941 3.396 6.038 4.495 8h9L21 12z");
}

</style>
