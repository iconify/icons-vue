<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4xjjczwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g4xjjczwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:image-fill" /></template>
