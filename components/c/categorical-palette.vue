<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-dg5fbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n-dg5fbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:categorical-palette" /></template>
