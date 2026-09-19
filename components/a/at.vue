<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3nv8zlly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w3nv8zlly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:at" /></template>
