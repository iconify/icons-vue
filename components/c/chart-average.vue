<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iz8_ibc7z.css';
import '../../css/r/rvab0qf4b.css';
import '../../css/v/v7_qmpb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iz8_ibc7z"/><path class="rvab0qf4b"/><path class="v7_qmpb8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart-average" /></template>
