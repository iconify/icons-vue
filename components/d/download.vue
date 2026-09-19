<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_zo3jt-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t_zo3jt-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:download" /></template>
