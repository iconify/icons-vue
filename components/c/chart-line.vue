<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-y34zbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-y34zbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:chart-line" /></template>
