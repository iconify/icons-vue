<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izft7ummp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="izft7ummp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watsonx-code-assistant-for-z-validation-assistant" /></template>
