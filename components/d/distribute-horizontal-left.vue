<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx30zxbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cx30zxbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:distribute-horizontal-left" /></template>
