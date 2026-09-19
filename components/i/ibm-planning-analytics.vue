<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrky55rmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mrky55rmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-planning-analytics" /></template>
