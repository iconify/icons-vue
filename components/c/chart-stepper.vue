<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqgem5-dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fqgem5-dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-stepper" /></template>
