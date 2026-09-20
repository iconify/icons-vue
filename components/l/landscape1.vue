<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq7ij0btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vq7ij0btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:landscape1" /></template>
