<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p11yxdbta.css';
import '../../css/x/xyb8xnbmc.css';
import '../../css/o/o-u2n4izs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="p11yxdbta"/><path class="xyb8xnbmc"/><path class="o-u2n4izs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-minus-bold" /></template>
