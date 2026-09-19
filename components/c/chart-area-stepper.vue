<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le-2l4b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="le-2l4b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-area-stepper" /></template>
