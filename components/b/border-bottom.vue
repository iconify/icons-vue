<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzqj45pit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pzqj45pit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:border-bottom" /></template>
