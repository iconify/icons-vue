<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hye2qnbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hye2qnbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-spline-solid" /></template>
