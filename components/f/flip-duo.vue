<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w3uhfdc8n.css';
import '../../css/o/o3dkww06e.css';
import '../../css/e/emipqme2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="w3uhfdc8n"/><path class="o3dkww06e"/><path class="emipqme2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:flip-duo" /></template>
