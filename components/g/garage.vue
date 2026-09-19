<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p1pnmsopg.css';
import '../../css/k/k8m56etkf.css';
import '../../css/h/hfw6dysas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p1pnmsopg"/><path class="k8m56etkf"/><path class="hfw6dysas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:garage" /></template>
