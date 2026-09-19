<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpu9l9bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lpu9l9bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ltc" /></template>
