<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6cinp7vj.css';
import '../../css/l/ly_uttqof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l6cinp7vj"/><path class="ly_uttqof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-process-mining" /></template>
