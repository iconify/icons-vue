<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyd1r-evo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyd1r-evo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-column-decreasing" /></template>
