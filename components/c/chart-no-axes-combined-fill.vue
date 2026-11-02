<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yao8nb-za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yao8nb-za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-no-axes-combined-fill" /></template>
