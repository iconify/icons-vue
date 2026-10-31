<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3wkoibbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3wkoibbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-info-fill-round" /></template>
