<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkb2mtbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kkb2mtbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-venn-diagram" /></template>
