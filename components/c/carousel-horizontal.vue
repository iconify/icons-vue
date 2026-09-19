<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf6_e5b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mf6_e5b9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:carousel-horizontal" /></template>
