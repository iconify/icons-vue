<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4sdsnbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a4sdsnbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-gg" /></template>
