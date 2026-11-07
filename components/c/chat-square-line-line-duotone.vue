<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d1fzfcc4g.css';
import '../../css/q/qf_ptnbfx.css';
import '../../css/c/cx31vwdjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d1fzfcc4g"/><path class="qf_ptnbfx"/><path class="cx31vwdjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-line-line-duotone" /></template>
