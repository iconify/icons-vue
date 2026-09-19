<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btwz3qbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="btwz3qbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-software-watsonx-data-structured-enrichment" /></template>
