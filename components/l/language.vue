<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf8q1q14h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zf8q1q14h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:language" /></template>
