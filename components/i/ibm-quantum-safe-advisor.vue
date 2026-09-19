<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5dz6eb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d5dz6eb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-quantum-safe-advisor" /></template>
