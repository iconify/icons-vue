<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh86o1w7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh86o1w7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart-candle" /></template>
