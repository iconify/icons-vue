<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylolabndh.css';
import '../../css/c/c1x3yyvty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ylolabndh"/><path class="c1x3yyvty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-ai-financial-instrument-sustainability-check" /></template>
