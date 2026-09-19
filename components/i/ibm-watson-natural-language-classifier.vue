<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isv9qth2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="isv9qth2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-natural-language-classifier" /></template>
