<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wvwfn091t.css';
import '../../css/w/wgiykycqr.css';
import '../../css/i/ioatddbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="wvwfn091t"/><path class="wgiykycqr"/><path class="ioatddbeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-foward-bold" /></template>
