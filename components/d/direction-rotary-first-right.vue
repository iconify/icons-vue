<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqc1pecct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aqc1pecct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-rotary-first-right" /></template>
