<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_n99qbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x_n99qbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bpmn-compensation-fill" /></template>
