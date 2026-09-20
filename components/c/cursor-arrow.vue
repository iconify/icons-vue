<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrq7_2bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yrq7_2bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:cursor-arrow" /></template>
