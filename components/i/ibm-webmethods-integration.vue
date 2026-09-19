<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkkun1bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wkkun1bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-webmethods-integration" /></template>
