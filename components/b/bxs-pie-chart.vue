<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk-zo9b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk-zo9b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-pie-chart" /></template>
