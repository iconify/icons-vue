<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aocp3_gja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aocp3_gja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-webmethods-api-gateway" /></template>
