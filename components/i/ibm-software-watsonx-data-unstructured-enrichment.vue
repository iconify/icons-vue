<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efac48boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="efac48boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-software-watsonx-data-unstructured-enrichment" /></template>
