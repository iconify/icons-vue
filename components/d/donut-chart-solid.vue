<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghei44brf.css';
import '../../css/y/ygr7rgb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ghei44brf"/><path class="ygr7rgb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:donut-chart-solid" /></template>
