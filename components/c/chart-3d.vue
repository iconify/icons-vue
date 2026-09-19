<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp6yu-55v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sp6yu-55v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-3d" /></template>
