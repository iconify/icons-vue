<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca3p3fdcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ca3p3fdcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-ss" /></template>
