<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6dy7ob-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z6dy7ob-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-gate-keeper" /></template>
