<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwtoqccjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xwtoqccjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:iso" /></template>
