<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-hw2vnyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f-hw2vnyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:area-range-dashed" /></template>
