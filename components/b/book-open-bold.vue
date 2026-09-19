<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s39efpwen.css';
import '../../css/u/ucu_1lbpn.css';
import '../../css/h/hscz_labj.css';
import '../../css/v/vbo612euk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="s39efpwen"/><path class="ucu_1lbpn"/><path clip-rule="evenodd" class="hscz_labj"/><path class="vbo612euk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:book-open-bold" /></template>
