<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngpfvz0la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ngpfvz0la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-line-data" /></template>
