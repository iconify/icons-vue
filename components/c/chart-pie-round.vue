<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvv-gcbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvv-gcbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pie-round" /></template>
