<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkdtpob8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gkdtpob8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-area-smooth" /></template>
