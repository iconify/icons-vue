<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0ax__bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y0ax__bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gateway-parallel-alt" /></template>
