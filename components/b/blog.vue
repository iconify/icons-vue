<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7moebfcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c7moebfcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:blog" /></template>
