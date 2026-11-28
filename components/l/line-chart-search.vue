<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1-ih3vjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1-ih3vjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:line-chart-search" /></template>
