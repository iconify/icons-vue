<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbhxcpbvt.css';
import '../../css/h/hd8ss2bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vbhxcpbvt"/><path class="hd8ss2bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:book" /></template>
