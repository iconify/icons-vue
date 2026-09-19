<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj55e6wen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aj55e6wen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-aa-large" /></template>
