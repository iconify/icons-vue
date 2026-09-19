<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wglng-x4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wglng-x4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bdl" /></template>
