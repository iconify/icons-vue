<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymp_cgxhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ymp_cgxhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:arrow-outline-up" /></template>
