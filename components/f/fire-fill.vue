<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_zd6wb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c_zd6wb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fire-fill" /></template>
