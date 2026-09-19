<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1rwnbp7q.css';
import '../../css/q/qru7a6bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c1rwnbp7q"/><path class="qru7a6bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-glassdoor" /></template>
