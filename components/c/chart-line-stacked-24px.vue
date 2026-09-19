<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgemnxrla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgemnxrla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-line-stacked-24px" /></template>
