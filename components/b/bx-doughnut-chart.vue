<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6dujwbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6dujwbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-doughnut-chart" /></template>
