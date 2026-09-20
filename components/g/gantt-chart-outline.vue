<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c29l7mb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c29l7mb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:gantt-chart-outline" /></template>
