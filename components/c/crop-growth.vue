<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3s0qsbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e3s0qsbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:crop-growth" /></template>
