<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqg7xdbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqg7xdbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:donut-chart" /></template>
