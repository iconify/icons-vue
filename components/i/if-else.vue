<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te45mhbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="te45mhbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:if-else" /></template>
