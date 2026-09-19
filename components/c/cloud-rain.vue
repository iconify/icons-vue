<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1zkl6b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x1zkl6b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-rain" /></template>
