<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf0p2l6ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yf0p2l6ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-quantum-safe-remediator" /></template>
