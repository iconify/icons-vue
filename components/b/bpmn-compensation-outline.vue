<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gte1i1jyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gte1i1jyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bpmn-compensation-outline" /></template>
