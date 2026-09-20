<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/uplssbb3f.css';
import '../../css/u/uw1yqtb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uplssbb3f"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.5s" values="16;0"/></path><path stroke-dashoffset="10" class="uw1yqtb0q"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.5s" dur="0.2s" to="0"/></path></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-long-diagonal" /></template>
