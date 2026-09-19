<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4gm1rbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n4gm1rbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:currency-ruble" /></template>
