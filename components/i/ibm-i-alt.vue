<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rat7_dmns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rat7_dmns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-i-alt" /></template>
