<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1-jxblam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i1-jxblam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:locked" /></template>
