<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6y3f0b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g6y3f0b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chevron-left" /></template>
