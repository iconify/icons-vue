<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3ivimbut.css';
import '../../css/n/ne1liqbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o3ivimbut"/><path class="ne1liqbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bar-horizontal-20" /></template>
