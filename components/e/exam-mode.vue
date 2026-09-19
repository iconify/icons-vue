<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x76te59bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x76te59bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:exam-mode" /></template>
