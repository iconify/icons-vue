<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0arns5nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c0arns5nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:file-diff" /></template>
