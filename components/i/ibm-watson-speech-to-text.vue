<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttidz-lwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ttidz-lwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-speech-to-text" /></template>
