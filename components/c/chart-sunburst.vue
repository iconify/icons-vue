<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8ms19yvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f8ms19yvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-sunburst" /></template>
