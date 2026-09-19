<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9cux6ikc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e9cux6ikc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:eraser" /></template>
