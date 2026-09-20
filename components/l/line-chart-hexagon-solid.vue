<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz6pdghwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz6pdghwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:line-chart-hexagon-solid" /></template>
