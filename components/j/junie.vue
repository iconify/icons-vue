<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzzb1zy8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nzzb1zy8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:junie" /></template>
