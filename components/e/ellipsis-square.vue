<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/h/hxgyvsbny.css';
import '../../css/e/exvi9zkwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="h01tyzbfu"><path class="hxgyvsbny"/><path class="exvi9zkwm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ellipsis-square" /></template>
