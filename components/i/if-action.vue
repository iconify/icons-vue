<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzgvacb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nzgvacb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:if-action" /></template>
