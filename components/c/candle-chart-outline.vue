<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9--h4bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u9--h4bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:candle-chart-outline" /></template>
