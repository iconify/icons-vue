<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1i2_yktj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1i2_yktj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chart-scatterplot-hexbin" /></template>
