<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw8lq1w4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw8lq1w4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:easyjet" /></template>
