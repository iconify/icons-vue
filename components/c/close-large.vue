<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi2q6_b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oi2q6_b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:close-large" /></template>
