<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlmp_l8be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlmp_l8be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-check-round" /></template>
