<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rrnwx6buh.css';
import '../../css/p/pr3cdbb2n.css';
import '../../css/c/cx31vwdjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rrnwx6buh"/><path class="pr3cdbb2n"/><path class="cx31vwdjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-line-linear" /></template>
