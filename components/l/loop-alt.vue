<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx_x97izc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kx_x97izc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:loop-alt" /></template>
