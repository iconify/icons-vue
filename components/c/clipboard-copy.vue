<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/u/u8xmwksak.css';
import '../../css/p/p-wxpmsdv.css';
import '../../css/w/w1cu-249y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="u8xmwksak"/><path class="p-wxpmsdv"/><path class="w1cu-249y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:clipboard-copy" /></template>
