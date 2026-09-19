<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e98t4kbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e98t4kbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-consulting-advantage-application" /></template>
