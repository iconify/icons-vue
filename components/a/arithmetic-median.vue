<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_dy700on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q_dy700on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arithmetic-median" /></template>
