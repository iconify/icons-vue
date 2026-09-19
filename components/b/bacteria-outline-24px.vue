<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/ncp7bccaf.css';
import '../../css/c/cx0dbdbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ncp7bccaf"/><path clip-rule="evenodd" class="cx0dbdbaq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bacteria-outline-24px" /></template>
