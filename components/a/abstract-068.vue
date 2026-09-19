<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd4n9pdfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jd4n9pdfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-068" /></template>
