<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l9x_x5b4e.css';
import '../../css/c/c7zikwrvh.css';
import '../../css/f/f08krvjen.css';
import '../../css/x/xc_fo9bdv.css';
import '../../css/f/f26ggybga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l9x_x5b4e"/><path class="c7zikwrvh"/><path class="f08krvjen"/><path class="xc_fo9bdv"/><path class="f26ggybga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fridge-linear" /></template>
