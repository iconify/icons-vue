<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i0or3xbtg.css';
import '../../css/t/tl-llyxxg.css';
import '../../css/g/gllij1bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="i0or3xbtg"/><path class="tl-llyxxg"/><path class="gllij1bxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:houses" /></template>
