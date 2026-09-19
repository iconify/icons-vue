<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wgu_60bdz.css';
import '../../css/n/nj8gx4bfi.css';
import '../../css/e/essrxs0ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="wgu_60bdz"/><path clip-rule="evenodd" class="nj8gx4bfi"/><path class="essrxs0ax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:clock-fast-bold" /></template>
