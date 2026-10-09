<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny-w6qbwa.css';
import '../../css/m/m8tnmwbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ny-w6qbwa"/><path class="m8tnmwbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:esg-report-20-bold" /></template>
