<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afv-v0b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="afv-v0b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-dual-y-axis" /></template>
