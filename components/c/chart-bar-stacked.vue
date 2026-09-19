<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0h1vccah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k0h1vccah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-bar-stacked" /></template>
