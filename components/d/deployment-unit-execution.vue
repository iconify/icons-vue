<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeadyab1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zeadyab1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:deployment-unit-execution" /></template>
