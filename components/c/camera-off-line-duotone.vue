<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nlh-17byn.css';
import '../../css/u/u4qnnrb5s.css';
import '../../css/f/fppjq7biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nlh-17byn"/><path class="u4qnnrb5s"/><path class="fppjq7biv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-off-line-duotone" /></template>
