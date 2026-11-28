<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc9fepjks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc9fepjks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bar-chart-horizontal" /></template>
