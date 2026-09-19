<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkrrj1btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qkrrj1btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:currency-dollar" /></template>
