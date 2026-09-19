<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw7q8-jnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yw7q8-jnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:graph-aggregator" /></template>
