<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccekybpeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccekybpeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-pie-chart-alt" /></template>
