<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv0wkklle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cv0wkklle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:center-square" /></template>
