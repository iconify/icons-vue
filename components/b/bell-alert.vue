<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rvw1gjbmf.css';
import '../../css/y/y5tcy_bsg.css';
import '../../css/i/i_ybz0bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rvw1gjbmf"/><path clip-rule="evenodd" class="y5tcy_bsg"/><path class="i_ybz0bjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bell-alert" /></template>
