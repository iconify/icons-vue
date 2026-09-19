<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vwoz82bix.css';
import '../../css/h/hsfk00bqh.css';
import '../../css/j/jtwksbc3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="vwoz82bix"/><path class="hsfk00bqh"/><path clip-rule="evenodd" class="jtwksbc3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:handshake" /></template>
