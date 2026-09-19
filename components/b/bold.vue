<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w856n9bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1536};
const content = `<path class="w856n9bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bold" /></template>
