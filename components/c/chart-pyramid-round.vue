<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx8_y6bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx8_y6bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid-round" /></template>
