<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9f_hdcju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r9f_hdcju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:job-run" /></template>
