<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on92ny6gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="on92ny6gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-volume" /></template>
