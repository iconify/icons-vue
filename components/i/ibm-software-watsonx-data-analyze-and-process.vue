<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4_b-eaap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t4_b-eaap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-software-watsonx-data-analyze-and-process" /></template>
