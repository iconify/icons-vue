<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek4yftbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ek4yftbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:batch-job-step" /></template>
