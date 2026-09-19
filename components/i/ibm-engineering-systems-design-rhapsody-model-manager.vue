<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px8l8sr1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="px8l8sr1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-engineering-systems-design-rhapsody-model-manager" /></template>
