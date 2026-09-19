<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_wq1vbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a_wq1vbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-toolchain" /></template>
