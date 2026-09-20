<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma1xzssnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ma1xzssnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:donut-chart-outline" /></template>
