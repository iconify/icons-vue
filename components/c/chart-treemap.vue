<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlp2sxb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mlp2sxb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-treemap" /></template>
