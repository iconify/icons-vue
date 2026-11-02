<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2eyk7blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2eyk7blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-column-stacked-fill" /></template>
