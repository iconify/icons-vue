<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysraz6bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ysraz6bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-class" /></template>
