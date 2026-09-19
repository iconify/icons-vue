<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_32gz_1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="e_32gz_1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:dailymotion" /></template>
