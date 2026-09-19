<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1rt0mcpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m1rt0mcpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:expand-screen-filled" /></template>
