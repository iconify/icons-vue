<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6yn1hbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q6yn1hbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-webmethods-developer-portal" /></template>
