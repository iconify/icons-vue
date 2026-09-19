<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgx4fhnbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mgx4fhnbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:analytics-reference" /></template>
