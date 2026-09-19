<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxo0d_b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nxo0d_b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-essential-security-and-observability-services" /></template>
