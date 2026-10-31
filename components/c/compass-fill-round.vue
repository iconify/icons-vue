<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5g2cq1iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5g2cq1iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:compass-fill-round" /></template>
