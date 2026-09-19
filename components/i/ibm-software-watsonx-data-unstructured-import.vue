<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyz1-gphb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cyz1-gphb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-software-watsonx-data-unstructured-import" /></template>
