<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy8javlss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1792};
const content = `<path class="yy8javlss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:houzz" /></template>
