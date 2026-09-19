<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uih3f9bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uih3f9bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:carbon-accounting" /></template>
