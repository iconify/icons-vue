<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7n3ylmey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7n3ylmey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bar-chart" /></template>
