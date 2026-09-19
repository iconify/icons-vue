<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1x3--bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y1x3--bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:earth-americas-filled" /></template>
