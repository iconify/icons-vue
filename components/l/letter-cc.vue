<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixid9lbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ixid9lbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-cc" /></template>
