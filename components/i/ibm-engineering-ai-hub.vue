<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eywq5cbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eywq5cbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-engineering-ai-hub" /></template>
